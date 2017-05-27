# stream
Clone from http://www.cs.virginia.edu/stream/

#### Sustainable Memory Bandwidth in High Performance Computers

---

## Quick Start

---

    cd STREAM/

    gcc -O -fopenmp stream.c -o stream_omp -DSTREAM_TYPE=double -DSTREAM_ARRAY_SIZE=256000000 -DOFFSET=56 -mcmodel=medium -DVERBOSE -DTUNED
    
    export OMP_NUM_THREADS=28
    
    ./stream_om
