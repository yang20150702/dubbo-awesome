# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.500 ops/ms
# Warmup Iteration   2: 11.798 ops/ms
# Warmup Iteration   3: 12.184 ops/ms
Iteration   1: 12.454 ops/ms
Iteration   2: 12.222 ops/ms
Iteration   3: 12.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.379 ±(99.9%) 2.483 ops/ms [Average]
  (min, avg, max) = (12.222, 12.379, 12.461), stdev = 0.136
  CI (99.9%): [9.896, 14.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.745 ops/ms
# Warmup Iteration   2: 12.455 ops/ms
# Warmup Iteration   3: 13.024 ops/ms
Iteration   1: 13.014 ops/ms
Iteration   2: 12.925 ops/ms
Iteration   3: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.922 ±(99.9%) 1.724 ops/ms [Average]
  (min, avg, max) = (12.825, 12.922, 13.014), stdev = 0.094
  CI (99.9%): [11.198, 14.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.954 ops/ms
# Warmup Iteration   2: 12.575 ops/ms
# Warmup Iteration   3: 12.931 ops/ms
Iteration   1: 12.941 ops/ms
Iteration   2: 12.774 ops/ms
Iteration   3: 12.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.859 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (12.774, 12.859, 12.941), stdev = 0.083
  CI (99.9%): [11.343, 14.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.664 ops/ms
# Warmup Iteration   2: 10.318 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.485 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.504 ±(99.9%) 0.343 ops/ms [Average]
  (min, avg, max) = (10.485, 10.504, 10.522), stdev = 0.019
  CI (99.9%): [10.161, 10.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.525, 2.540, 2.561), stdev = 0.018
  CI (99.9%): [2.206, 2.875] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.003 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.480, 2.488, 2.503), stdev = 0.013
  CI (99.9%): [2.259, 2.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
Iteration   3: 2.530 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.532 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.515, 2.532, 2.552), stdev = 0.019
  CI (99.9%): [2.187, 2.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
Iteration   2: 3.025 ±(99.9%) 0.004 ms/op
Iteration   3: 3.000 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.004 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.986, 3.004, 3.025), stdev = 0.020
  CI (99.9%): [2.642, 3.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  11.118 ms/op
                 createUser·p0.9999: 13.936 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  9.915 ms/op
                 createUser·p0.9999: 11.730 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.572 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.076 ms/op
                 createUser·p0.999:  9.383 ms/op
                 createUser·p0.9999: 12.052 ms/op
                 createUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374560
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180226 
    [ 2.500,  3.750) = 189899 
    [ 3.750,  5.000) = 3426 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.848 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     13.143 ms/op
     p(99.9990) =     14.938 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  5.903 ms/op
                 existUser·p0.9999: 13.551 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  5.476 ms/op
                 existUser·p0.9999: 13.568 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  6.672 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388949
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 191421 
    [ 2.500,  3.750) = 194682 
    [ 3.750,  5.000) = 2192 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      5.907 ms/op
     p(99.9900) =     13.068 ms/op
     p(99.9990) =     14.403 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  11.297 ms/op
                 getUser·p0.9999: 14.127 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  6.125 ms/op
                 getUser·p0.9999: 12.243 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  9.033 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382790
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 188793 
    [ 2.500,  3.750) = 190202 
    [ 3.750,  5.000) = 3042 
    [ 5.000,  6.250) = 304 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      6.836 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     14.227 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.009 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.407 ms/op
                 listUser·p0.9999: 10.951 ms/op
                 listUser·p1.00:   11.239 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.819 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.526 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316378
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 87183 
    [ 2.500,  3.750) = 189036 
    [ 3.750,  5.000) = 33149 
    [ 5.000,  6.250) = 5680 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.999 ms/op
     p(99.9990) =     12.941 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.379 ± 2.483  ops/ms
ClientPb.existUser                       thrpt       3  12.922 ± 1.724  ops/ms
ClientPb.getUser                         thrpt       3  12.859 ± 1.516  ops/ms
ClientPb.listUser                        thrpt       3  10.504 ± 0.343  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.334   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.229   ms/op
ClientPb.getUser                          avgt       3   2.532 ± 0.346   ms/op
ClientPb.listUser                         avgt       3   3.004 ± 0.362   ms/op
ClientPb.createUser                     sample  374560   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.810           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.848           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.421           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.143           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.941           ms/op
ClientPb.existUser                      sample  388949   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.623           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.907           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  382790   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.736           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.836           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.352           ms/op
ClientPb.listUser                       sample  316378   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.999           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
