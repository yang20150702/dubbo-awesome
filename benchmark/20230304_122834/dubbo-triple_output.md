# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.802 ops/ms
# Warmup Iteration   2: 7.221 ops/ms
# Warmup Iteration   3: 9.212 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 10.163 ops/ms
Iteration   3: 9.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.829 ±(99.9%) 5.288 ops/ms [Average]
  (min, avg, max) = (9.640, 9.829, 10.163), stdev = 0.290
  CI (99.9%): [4.541, 15.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ops/ms
# Warmup Iteration   2: 9.276 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.193 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.440 ±(99.9%) 3.964 ops/ms [Average]
  (min, avg, max) = (10.193, 10.440, 10.599), stdev = 0.217
  CI (99.9%): [6.476, 14.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ops/ms
# Warmup Iteration   2: 9.127 ops/ms
# Warmup Iteration   3: 9.645 ops/ms
Iteration   1: 10.321 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 10.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.119 ±(99.9%) 3.350 ops/ms [Average]
  (min, avg, max) = (9.963, 10.119, 10.321), stdev = 0.184
  CI (99.9%): [6.769, 13.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ops/ms
# Warmup Iteration   2: 7.873 ops/ms
# Warmup Iteration   3: 8.388 ops/ms
Iteration   1: 8.749 ops/ms
Iteration   2: 8.567 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.629 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (8.567, 8.629, 8.749), stdev = 0.104
  CI (99.9%): [6.723, 10.534] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.614 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.007 ms/op
Iteration   1: 3.257 ±(99.9%) 0.007 ms/op
Iteration   2: 3.295 ±(99.9%) 0.007 ms/op
Iteration   3: 3.263 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.272 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.257, 3.272, 3.295), stdev = 0.020
  CI (99.9%): [2.905, 3.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.261 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.009 ms/op
Iteration   1: 3.185 ±(99.9%) 0.006 ms/op
Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
Iteration   3: 3.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 1.771 ms/op [Average]
  (min, avg, max) = (3.011, 3.123, 3.185), stdev = 0.097
  CI (99.9%): [1.352, 4.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.004 ms/op
Iteration   1: 3.238 ±(99.9%) 0.008 ms/op
Iteration   2: 3.305 ±(99.9%) 0.005 ms/op
Iteration   3: 3.200 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.200, 3.248, 3.305), stdev = 0.053
  CI (99.9%): [2.277, 4.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.073 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.006 ms/op
Iteration   1: 3.677 ±(99.9%) 0.011 ms/op
Iteration   2: 3.783 ±(99.9%) 0.004 ms/op
Iteration   3: 3.757 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.677, 3.739, 3.783), stdev = 0.056
  CI (99.9%): [2.725, 4.753] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.127 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
Iteration   1: 3.208 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  13.521 ms/op
                 createUser·p0.9999: 20.514 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  10.213 ms/op
                 createUser·p0.9999: 21.587 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 3.421 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  16.187 ms/op
                 createUser·p0.9999: 17.651 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295361
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20802 
    [ 2.500,  5.000) = 267948 
    [ 5.000,  7.500) = 5771 
    [ 7.500, 10.000) = 386 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.864 ms/op
     p(99.9900) =     20.871 ms/op
     p(99.9990) =     21.694 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.735 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.141 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   4.940 ms/op
                 existUser·p0.999:  12.976 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 3.148 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  14.073 ms/op
                 existUser·p0.9999: 27.417 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305439
  mean =      3.142 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17603 
    [ 2.500,  5.000) = 283378 
    [ 5.000,  7.500) = 3522 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     26.087 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
Iteration   1: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  16.992 ms/op
                 getUser·p0.9999: 21.168 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  9.171 ms/op
                 getUser·p0.9999: 26.236 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 20.936 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301395
  mean =      3.181 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16297 
    [ 2.500,  5.000) = 278212 
    [ 5.000,  7.500) = 6042 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     16.574 ms/op
     p(99.9900) =     24.843 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.786 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.012 ms/op
Iteration   1: 3.751 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.051 ms/op
                 listUser·p0.999:  15.084 ms/op
                 listUser·p0.9999: 21.100 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 3.698 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.519 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.499 ms/op
                 listUser·p0.9999: 13.648 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256277
  mean =      3.744 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 248207 
    [ 5.000,  7.500) = 6428 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     19.280 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.829 ± 5.288  ops/ms
ClientPb.existUser                       thrpt       3  10.440 ± 3.964  ops/ms
ClientPb.getUser                         thrpt       3  10.119 ± 3.350  ops/ms
ClientPb.listUser                        thrpt       3   8.629 ± 1.906  ops/ms
ClientPb.createUser                       avgt       3   3.272 ± 0.367   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 1.771   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 0.971   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 1.014   ms/op
ClientPb.createUser                     sample  295361   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.725           ms/op
ClientPb.existUser                      sample  305439   3.142 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  301395   3.181 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.040           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.574           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.843           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  256277   3.744 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.271           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.987           ms/op
