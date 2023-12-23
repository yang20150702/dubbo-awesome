# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.282 ops/ms
# Warmup Iteration   2: 12.150 ops/ms
# Warmup Iteration   3: 12.234 ops/ms
Iteration   1: 12.391 ops/ms
Iteration   2: 12.589 ops/ms
Iteration   3: 12.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.536 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (12.391, 12.536, 12.628), stdev = 0.127
  CI (99.9%): [10.221, 14.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.669 ops/ms
# Warmup Iteration   2: 13.128 ops/ms
# Warmup Iteration   3: 13.010 ops/ms
Iteration   1: 13.098 ops/ms
Iteration   2: 13.165 ops/ms
Iteration   3: 13.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.154 ±(99.9%) 0.955 ops/ms [Average]
  (min, avg, max) = (13.098, 13.154, 13.201), stdev = 0.052
  CI (99.9%): [12.199, 14.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.032 ops/ms
# Warmup Iteration   2: 12.285 ops/ms
# Warmup Iteration   3: 12.729 ops/ms
Iteration   1: 12.699 ops/ms
Iteration   2: 12.882 ops/ms
Iteration   3: 12.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.803 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (12.699, 12.803, 12.882), stdev = 0.094
  CI (99.9%): [11.094, 14.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.571 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 10.770 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.645 ±(99.9%) 0.654 ops/ms [Average]
  (min, avg, max) = (10.604, 10.645, 10.667), stdev = 0.036
  CI (99.9%): [9.991, 11.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (2.516, 2.536, 2.573), stdev = 0.032
  CI (99.9%): [1.950, 3.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.630 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.453, 2.469, 2.490), stdev = 0.019
  CI (99.9%): [2.118, 2.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.003 ms/op
Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.461, 2.470, 2.487), stdev = 0.015
  CI (99.9%): [2.189, 2.751] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.977 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
Iteration   3: 3.017 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.017, 3.029, 3.046), stdev = 0.015
  CI (99.9%): [2.747, 3.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 16.499 ms/op
                 createUser·p1.00:   17.564 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.952 ms/op
                 createUser·p0.9999: 13.500 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.004 ms/op
                 createUser·p0.9999: 15.373 ms/op
                 createUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377797
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 184652 
    [ 2.500,  3.750) = 185863 
    [ 3.750,  5.000) = 6039 
    [ 5.000,  6.250) = 669 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     15.548 ms/op
     p(99.9990) =     16.633 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.390 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.363 ±(99.9%) 0.006 ms/op
Iteration   1: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.347 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  5.744 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.357 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.290 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 13.007 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.357 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   2.306 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  8.075 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 405152
  mean =      2.367 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 256 
    [ 1.250,  2.500) = 238558 
    [ 2.500,  3.750) = 161264 
    [ 3.750,  5.000) = 4215 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      7.362 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.691 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  5.534 ms/op
                 getUser·p0.9999: 16.384 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  9.279 ms/op
                 getUser·p0.9999: 17.292 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  8.848 ms/op
                 getUser·p0.9999: 12.079 ms/op
                 getUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382327
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 188303 
    [ 2.500,  3.750) = 187980 
    [ 3.750,  5.000) = 4723 
    [ 5.000,  6.250) = 815 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      6.829 ms/op
     p(99.9900) =     16.384 ms/op
     p(99.9990) =     18.094 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.664 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.551 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.818 ms/op
                 listUser·p0.9999: 11.684 ms/op
                 listUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315152
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 86173 
    [ 2.500,  3.750) = 187995 
    [ 3.750,  5.000) = 33706 
    [ 5.000,  6.250) = 5854 
    [ 6.250,  7.500) = 597 
    [ 7.500,  8.750) = 255 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.615 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     13.019 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.536 ± 2.315  ops/ms
ClientPb.existUser                       thrpt       3  13.154 ± 0.955  ops/ms
ClientPb.getUser                         thrpt       3  12.803 ± 1.709  ops/ms
ClientPb.listUser                        thrpt       3  10.645 ± 0.654  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.586   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.351   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.281   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.282   ms/op
ClientPb.createUser                     sample  377797   2.539 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.700           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.548           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.564           ms/op
ClientPb.existUser                      sample  405152   2.367 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.584           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.362           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  382327   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.829           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.384           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.038           ms/op
ClientPb.listUser                       sample  315152   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
