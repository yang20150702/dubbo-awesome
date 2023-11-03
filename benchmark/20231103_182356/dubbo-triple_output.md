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
# Warmup Iteration   1: 4.791 ops/ms
# Warmup Iteration   2: 11.930 ops/ms
# Warmup Iteration   3: 12.400 ops/ms
Iteration   1: 12.740 ops/ms
Iteration   2: 12.725 ops/ms
Iteration   3: 12.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.765 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (12.725, 12.765, 12.831), stdev = 0.057
  CI (99.9%): [11.720, 13.811] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.071 ops/ms
# Warmup Iteration   2: 13.000 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 13.169 ops/ms
Iteration   2: 13.177 ops/ms
Iteration   3: 13.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.171 ±(99.9%) 0.089 ops/ms [Average]
  (min, avg, max) = (13.168, 13.171, 13.177), stdev = 0.005
  CI (99.9%): [13.082, 13.260] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.097 ops/ms
# Warmup Iteration   2: 12.812 ops/ms
# Warmup Iteration   3: 12.999 ops/ms
Iteration   1: 13.000 ops/ms
Iteration   2: 12.991 ops/ms
Iteration   3: 13.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.026 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (12.991, 13.026, 13.088), stdev = 0.054
  CI (99.9%): [12.049, 14.004] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.771 ops/ms
# Warmup Iteration   2: 10.483 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.713 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.625 ±(99.9%) 1.907 ops/ms [Average]
  (min, avg, max) = (10.509, 10.625, 10.713), stdev = 0.105
  CI (99.9%): [8.717, 12.532] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.475, 2.491, 2.506), stdev = 0.015
  CI (99.9%): [2.209, 2.774] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.731 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
Iteration   3: 2.448 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.437 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.420, 2.437, 2.448), stdev = 0.015
  CI (99.9%): [2.170, 2.704] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.479 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.464, 2.479, 2.502), stdev = 0.020
  CI (99.9%): [2.112, 2.845] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
Iteration   3: 3.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (3.015, 3.019, 3.026), stdev = 0.006
  CI (99.9%): [2.914, 3.124] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   4.274 ms/op
                 createUser·p0.999:  11.065 ms/op
                 createUser·p0.9999: 13.200 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.490 ms/op
                 createUser·p0.999:  5.860 ms/op
                 createUser·p0.9999: 12.258 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.042 ms/op
                 createUser·p0.9999: 23.153 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384363
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185645 
    [ 2.500,  5.000) = 197449 
    [ 5.000,  7.500) = 822 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      9.038 ms/op
     p(99.9900) =     13.814 ms/op
     p(99.9990) =     23.467 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.813 ms/op
                 existUser·p0.9999: 13.469 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 11.780 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.623 ms/op
                 existUser·p0.999:  6.160 ms/op
                 existUser·p0.9999: 11.975 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389991
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 191805 
    [ 2.500,  3.750) = 194780 
    [ 3.750,  5.000) = 2549 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      6.078 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     13.617 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  6.090 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  9.268 ms/op
                 getUser·p0.9999: 15.696 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  7.186 ms/op
                 getUser·p0.9999: 10.541 ms/op
                 getUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387057
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 194255 
    [ 2.500,  3.750) = 188187 
    [ 3.750,  5.000) = 3496 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     13.898 ms/op
     p(99.9990) =     15.825 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.643 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.470 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.469 ms/op
                 listUser·p0.9999: 11.375 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.894 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320660
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 97301 
    [ 2.500,  3.750) = 184953 
    [ 3.750,  5.000) = 31141 
    [ 5.000,  6.250) = 5839 
    [ 6.250,  7.500) = 578 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.394 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.298 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.765 ± 1.045  ops/ms
ClientPb.existUser                       thrpt       3  13.171 ± 0.089  ops/ms
ClientPb.getUser                         thrpt       3  13.026 ± 0.978  ops/ms
ClientPb.listUser                        thrpt       3  10.625 ± 1.907  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   2.437 ± 0.267   ms/op
ClientPb.getUser                          avgt       3   2.479 ± 0.367   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.105   ms/op
ClientPb.createUser                     sample  384363   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.864           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.038           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.814           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.379           ms/op
ClientPb.existUser                      sample  389991   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.865           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.877           ms/op
ClientPb.getUser                        sample  387057   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.873           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.898           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.991           ms/op
ClientPb.listUser                       sample  320660   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.583           ms/op
