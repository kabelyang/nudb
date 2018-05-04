NuDB is an append-only, key/value store specifically optimized for random read performance on modern SSDs or equivalent high-IOPS devices. 
<br>The most common application for NuDB is content addressable storage where a cryptographic digest of the data is used as the key.
<br>The read performance and memory usage are independent of the size of the database. These are some other features:
<br>
<br>Low memory footprint
<br>Database size up to 281TB
<br>All keys are the same size
<br>Append-only, no update or delete
<br>Value sizes from 1 to 2^32 bytes (4GB)
<br>Performance independent of growth
<br>Optimized for concurrent fetch
<br>Key file can be rebuilt if needed
<br>Inserts are atomic and consistent
<br>Data file may be efficiently iterated
<br>Key and data files may be on different devices
<br>Hardened against algorithmic complexity attacks
<br>Header-only, no separate library to build
<br>
<b>Requirements:</b><br>
<br>Boost 1.58 or higher
<br>C++11 or greater
<br>SSD drive, or equivalent device with high IOPS
