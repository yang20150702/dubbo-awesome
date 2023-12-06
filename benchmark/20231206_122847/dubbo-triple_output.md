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
# Warmup Iteration   1: 4.596 ops/ms
# Warmup Iteration   2: 11.803 ops/ms
# Warmup Iteration   3: 12.143 ops/ms
Iteration   1: 12.523 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.629 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (12.523, 12.629, 12.782), stdev = 0.135
  CI (99.9%): [10.161, 15.098] (assumes normal distribution)


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
# Warmup Iteration   1: 8.159 ops/ms
# Warmup Iteration   2: 13.123 ops/ms
# Warmup Iteration   3: 13.093 ops/ms
Iteration   1: 12.897 ops/ms
Iteration   2: 13.039 ops/ms
Iteration   3: 13.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.003 ±(99.9%) 1.702 ops/ms [Average]
  (min, avg, max) = (12.897, 13.003, 13.072), stdev = 0.093
  CI (99.9%): [11.301, 14.704] (assumes normal distribution)


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
# Warmup Iteration   1: 8.092 ops/ms
# Warmup Iteration   2: 12.461 ops/ms
# Warmup Iteration   3: 12.740 ops/ms
Iteration   1: 12.943 ops/ms
Iteration   2: 12.881 ops/ms
Iteration   3: 12.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.773 ±(99.9%) 4.424 ops/ms [Average]
  (min, avg, max) = (12.496, 12.773, 12.943), stdev = 0.242
  CI (99.9%): [8.349, 17.197] (assumes normal distribution)


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
# Warmup Iteration   1: 6.501 ops/ms
# Warmup Iteration   2: 10.406 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.561 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (10.499, 10.561, 10.633), stdev = 0.068
  CI (99.9%): [9.323, 11.800] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.003 ms/op
Iteration   3: 2.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.525 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (2.504, 2.525, 2.565), stdev = 0.035
  CI (99.9%): [1.895, 3.155] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.003 ms/op
Iteration   1: 2.446 ±(99.9%) 0.003 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.428, 2.435, 2.446), stdev = 0.009
  CI (99.9%): [2.270, 2.600] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.479, 2.492, 2.513), stdev = 0.018
  CI (99.9%): [2.159, 2.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.993 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.986, 2.993, 3.006), stdev = 0.011
  CI (99.9%): [2.794, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.572 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  11.557 ms/op
                 createUser·p0.9999: 13.676 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 13.339 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 10.639 ms/op
                 createUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376123
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 179871 
    [ 2.500,  3.750) = 189968 
    [ 3.750,  5.000) = 4730 
    [ 5.000,  6.250) = 941 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 153 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 127 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.053 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  7.032 ms/op
                 existUser·p0.9999: 14.696 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.422 ms/op
                 existUser·p0.9999: 13.254 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.902 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  6.893 ms/op
                 existUser·p0.9999: 11.320 ms/op
                 existUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391588
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 193298 
    [ 2.500,  3.750) = 194918 
    [ 3.750,  5.000) = 2534 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     15.056 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.274 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 13.655 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  9.399 ms/op
                 getUser·p0.9999: 14.606 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  8.852 ms/op
                 getUser·p0.9999: 12.227 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379309
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 185272 
    [ 2.500,  3.750) = 188130 
    [ 3.750,  5.000) = 4795 
    [ 5.000,  6.250) = 594 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      7.368 ms/op
     p(99.9900) =     13.748 ms/op
     p(99.9990) =     14.939 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.761 ms/op
                 listUser·p0.9999: 10.397 ms/op
                 listUser·p1.00:   11.207 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.728 ms/op
                 listUser·p0.999:  10.273 ms/op
                 listUser·p0.9999: 11.908 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.918 ms/op
                 listUser·p0.9999: 11.005 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311448
  mean =      3.080 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 81034 
    [ 2.500,  3.750) = 186357 
    [ 3.750,  5.000) = 35729 
    [ 5.000,  6.250) = 6662 
    [ 6.250,  7.500) = 864 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 208 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     11.576 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.629 ± 2.469  ops/ms
ClientPb.existUser                       thrpt       3  13.003 ± 1.702  ops/ms
ClientPb.getUser                         thrpt       3  12.773 ± 4.424  ops/ms
ClientPb.listUser                        thrpt       3  10.561 ± 1.239  ops/ms
ClientPb.createUser                       avgt       3   2.525 ± 0.630   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.165   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.333   ms/op
ClientPb.listUser                         avgt       3   2.993 ± 0.199   ms/op
ClientPb.createUser                     sample  376123   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.864           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.159           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.172           ms/op
ClientPb.existUser                      sample  391588   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.897           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.565           ms/op
ClientPb.getUser                        sample  379309   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.862           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.368           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.748           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.041           ms/op
ClientPb.listUser                       sample  311448   3.080 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
