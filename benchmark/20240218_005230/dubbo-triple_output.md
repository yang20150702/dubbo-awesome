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
# Warmup Iteration   1: 4.575 ops/ms
# Warmup Iteration   2: 11.801 ops/ms
# Warmup Iteration   3: 12.325 ops/ms
Iteration   1: 12.539 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.611 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (12.539, 12.611, 12.660), stdev = 0.063
  CI (99.9%): [11.459, 13.763] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ops/ms
# Warmup Iteration   2: 13.085 ops/ms
# Warmup Iteration   3: 12.980 ops/ms
Iteration   1: 13.161 ops/ms
Iteration   2: 13.169 ops/ms
Iteration   3: 13.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.153 ±(99.9%) 0.374 ops/ms [Average]
  (min, avg, max) = (13.130, 13.153, 13.169), stdev = 0.021
  CI (99.9%): [12.779, 13.528] (assumes normal distribution)


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
# Warmup Iteration   1: 7.115 ops/ms
# Warmup Iteration   2: 12.425 ops/ms
# Warmup Iteration   3: 12.641 ops/ms
Iteration   1: 12.659 ops/ms
Iteration   2: 12.558 ops/ms
Iteration   3: 12.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.659 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (12.558, 12.659, 12.759), stdev = 0.100
  CI (99.9%): [10.828, 14.490] (assumes normal distribution)


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
# Warmup Iteration   1: 6.712 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.743 ops/ms
Iteration   2: 10.751 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.732 ±(99.9%) 0.486 ops/ms [Average]
  (min, avg, max) = (10.702, 10.732, 10.751), stdev = 0.027
  CI (99.9%): [10.246, 11.218] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.277 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.528 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.520 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.514, 2.520, 2.528), stdev = 0.007
  CI (99.9%): [2.393, 2.648] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.842 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.003 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.475, 2.479, 2.483), stdev = 0.004
  CI (99.9%): [2.402, 2.555] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.505, 2.509, 2.515), stdev = 0.005
  CI (99.9%): [2.413, 2.605] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.005 ms/op
Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
Iteration   3: 3.020 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.030 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (3.020, 3.030, 3.036), stdev = 0.009
  CI (99.9%): [2.868, 3.191] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 13.705 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  9.644 ms/op
                 createUser·p0.9999: 12.787 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 11.411 ms/op
                 createUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376073
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 180105 
    [ 2.500,  3.750) = 191513 
    [ 3.750,  5.000) = 3477 
    [ 5.000,  6.250) = 463 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.830 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.329 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.116 ms/op
                 existUser·p0.9999: 13.747 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.122 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.745 ms/op
                 existUser·p0.9999: 12.093 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388287
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 190579 
    [ 2.500,  3.750) = 194197 
    [ 3.750,  5.000) = 2605 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.846 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.258 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  10.534 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  10.103 ms/op
                 getUser·p0.9999: 13.693 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  7.529 ms/op
                 getUser·p0.9999: 11.572 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382865
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 188534 
    [ 2.500,  3.750) = 189719 
    [ 3.750,  5.000) = 3507 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.981 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.326 ms/op
                 listUser·p0.9999: 10.949 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.288 ms/op
                 listUser·p0.9999: 11.877 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.485 ms/op
                 listUser·p0.9999: 10.787 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316928
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 88469 
    [ 2.500,  3.750) = 188505 
    [ 3.750,  5.000) = 32785 
    [ 5.000,  6.250) = 5708 
    [ 6.250,  7.500) = 677 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 287 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     12.078 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.611 ± 1.152  ops/ms
ClientPb.existUser                       thrpt       3  13.153 ± 0.374  ops/ms
ClientPb.getUser                         thrpt       3  12.659 ± 1.831  ops/ms
ClientPb.listUser                        thrpt       3  10.732 ± 0.486  ops/ms
ClientPb.createUser                       avgt       3   2.520 ± 0.128   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.076   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.096   ms/op
ClientPb.listUser                         avgt       3   3.030 ± 0.161   ms/op
ClientPb.createUser                     sample  376073   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.830           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.860           ms/op
ClientPb.existUser                      sample  388287   2.470 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.353           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  382865   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.981           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  316928   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.190           ms/op
