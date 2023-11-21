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
# Warmup Iteration   1: 4.624 ops/ms
# Warmup Iteration   2: 11.890 ops/ms
# Warmup Iteration   3: 12.333 ops/ms
Iteration   1: 12.298 ops/ms
Iteration   2: 12.585 ops/ms
Iteration   3: 12.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.531 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (12.298, 12.531, 12.709), stdev = 0.211
  CI (99.9%): [8.685, 16.377] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.722 ops/ms
# Warmup Iteration   2: 12.719 ops/ms
# Warmup Iteration   3: 12.786 ops/ms
Iteration   1: 12.849 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.803 ±(99.9%) 0.788 ops/ms [Average]
  (min, avg, max) = (12.764, 12.803, 12.849), stdev = 0.043
  CI (99.9%): [12.014, 13.591] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.300 ops/ms
# Warmup Iteration   2: 12.086 ops/ms
# Warmup Iteration   3: 12.415 ops/ms
Iteration   1: 12.493 ops/ms
Iteration   2: 12.539 ops/ms
Iteration   3: 12.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.515 ±(99.9%) 0.424 ops/ms [Average]
  (min, avg, max) = (12.493, 12.515, 12.539), stdev = 0.023
  CI (99.9%): [12.091, 12.938] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.522 ops/ms
# Warmup Iteration   2: 10.595 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.502 ±(99.9%) 1.778 ops/ms [Average]
  (min, avg, max) = (10.415, 10.502, 10.607), stdev = 0.097
  CI (99.9%): [8.725, 12.280] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.517, 2.523, 2.528), stdev = 0.006
  CI (99.9%): [2.413, 2.634] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.003 ms/op
Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.014 ms/op [Average]
  (min, avg, max) = (2.485, 2.486, 2.487), stdev = 0.001
  CI (99.9%): [2.472, 2.499] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.527 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.523, 2.527, 2.531), stdev = 0.004
  CI (99.9%): [2.457, 2.596] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
Iteration   3: 3.032 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.040 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.032, 3.040, 3.049), stdev = 0.009
  CI (99.9%): [2.880, 3.200] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.263 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.774 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.596 ±(99.9%) 0.006 ms/op
Iteration   1: 2.578 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  12.223 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.611 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  9.679 ms/op
                 createUser·p0.9999: 15.876 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   3: 2.615 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.178 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  9.190 ms/op
                 createUser·p0.9999: 13.038 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368495
  mean =      2.601 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174478 
    [ 2.500,  5.000) = 193103 
    [ 5.000,  7.500) = 519 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     14.515 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 3.704 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.514 ms/op
                 existUser·p0.9999: 14.522 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  9.169 ms/op
                 existUser·p0.9999: 15.286 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.256 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.827 ms/op
                 existUser·p0.9999: 11.786 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382780
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 188760 
    [ 2.500,  3.750) = 188963 
    [ 3.750,  5.000) = 3836 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      6.506 ms/op
     p(99.9900) =     14.954 ms/op
     p(99.9990) =     15.893 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  12.385 ms/op
                 getUser·p0.9999: 15.101 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 13.054 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 13.935 ms/op
                 getUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377330
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 183181 
    [ 2.500,  3.750) = 188588 
    [ 3.750,  5.000) = 4394 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      9.344 ms/op
     p(99.9900) =     14.619 ms/op
     p(99.9990) =     15.408 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.895 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.009 ms/op
Iteration   1: 3.088 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.256 ms/op
                 listUser·p0.9999: 12.926 ms/op
                 listUser·p1.00:   13.304 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.573 ms/op
                 listUser·p0.9999: 11.123 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.983 ms/op
                 listUser·p0.9999: 11.522 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310919
  mean =      3.084 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 80080 
    [ 2.500,  3.750) = 186662 
    [ 3.750,  5.000) = 35727 
    [ 5.000,  6.250) = 6963 
    [ 6.250,  7.500) = 717 
    [ 7.500,  8.750) = 168 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.534 ms/op
     p(99.9990) =     13.115 ms/op
     p(99.9999) =     13.304 ms/op
    p(100.0000) =     13.304 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.531 ± 3.846  ops/ms
ClientPb.existUser                       thrpt       3  12.803 ± 0.788  ops/ms
ClientPb.getUser                         thrpt       3  12.515 ± 0.424  ops/ms
ClientPb.listUser                        thrpt       3  10.502 ± 1.778  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.110   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.014   ms/op
ClientPb.getUser                          avgt       3   2.527 ± 0.070   ms/op
ClientPb.listUser                         avgt       3   3.040 ± 0.160   ms/op
ClientPb.createUser                     sample  368495   2.601 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.950           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.515           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.103           ms/op
ClientPb.existUser                      sample  382780   2.505 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.905           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.506           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.954           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.089           ms/op
ClientPb.getUser                        sample  377330   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.767           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.344           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.619           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  310919   3.084 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.534           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.304           ms/op
