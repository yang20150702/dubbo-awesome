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
# Warmup Iteration   1: 4.966 ops/ms
# Warmup Iteration   2: 11.933 ops/ms
# Warmup Iteration   3: 12.218 ops/ms
Iteration   1: 12.281 ops/ms
Iteration   2: 12.471 ops/ms
Iteration   3: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.438 ±(99.9%) 2.601 ops/ms [Average]
  (min, avg, max) = (12.281, 12.438, 12.561), stdev = 0.143
  CI (99.9%): [9.837, 15.039] (assumes normal distribution)


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
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 12.817 ops/ms
# Warmup Iteration   3: 12.835 ops/ms
Iteration   1: 12.785 ops/ms
Iteration   2: 13.027 ops/ms
Iteration   3: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.909 ±(99.9%) 2.212 ops/ms [Average]
  (min, avg, max) = (12.785, 12.909, 13.027), stdev = 0.121
  CI (99.9%): [10.698, 15.121] (assumes normal distribution)


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
# Warmup Iteration   1: 7.737 ops/ms
# Warmup Iteration   2: 12.424 ops/ms
# Warmup Iteration   3: 12.419 ops/ms
Iteration   1: 12.698 ops/ms
Iteration   2: 12.711 ops/ms
Iteration   3: 12.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.686 ±(99.9%) 0.598 ops/ms [Average]
  (min, avg, max) = (12.649, 12.686, 12.711), stdev = 0.033
  CI (99.9%): [12.088, 13.284] (assumes normal distribution)


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
# Warmup Iteration   1: 6.535 ops/ms
# Warmup Iteration   2: 10.333 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.492 ops/ms
Iteration   2: 10.410 ops/ms
Iteration   3: 10.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.433 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (10.397, 10.433, 10.492), stdev = 0.051
  CI (99.9%): [9.499, 11.368] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.567 ±(99.9%) 0.004 ms/op
Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.561 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (2.527, 2.561, 2.588), stdev = 0.031
  CI (99.9%): [1.995, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.470, 2.475, 2.484), stdev = 0.008
  CI (99.9%): [2.329, 2.621] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.501, 2.517, 2.534), stdev = 0.016
  CI (99.9%): [2.219, 2.816] (assumes normal distribution)


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.041 ±(99.9%) 0.095 ms/op [Average]
  (min, avg, max) = (3.035, 3.041, 3.046), stdev = 0.005
  CI (99.9%): [2.947, 3.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  10.914 ms/op
                 createUser·p0.9999: 13.836 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.607 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.427 ms/op
                 createUser·p0.9999: 12.165 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.598 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 10.076 ms/op
                 createUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370584
  mean =      2.588 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 174804 
    [ 2.500,  3.750) = 189551 
    [ 3.750,  5.000) = 4704 
    [ 5.000,  6.250) = 887 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.875 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.948 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.862 ms/op
                 existUser·p0.9999: 13.682 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.051 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 12.227 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385097
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 187356 
    [ 2.500,  3.750) = 193788 
    [ 3.750,  5.000) = 3090 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.520 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.409 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 13.615 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 13.954 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  8.276 ms/op
                 getUser·p0.9999: 11.000 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380236
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 185215 
    [ 2.500,  3.750) = 189673 
    [ 3.750,  5.000) = 4481 
    [ 5.000,  6.250) = 358 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 138 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.340 ms/op
     p(99.9900) =     13.516 ms/op
     p(99.9990) =     14.208 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  8.614 ms/op
                 listUser·p0.9999: 10.758 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.946 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315335
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 89454 
    [ 2.500,  3.750) = 183614 
    [ 3.750,  5.000) = 34054 
    [ 5.000,  6.250) = 6523 
    [ 6.250,  7.500) = 928 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.156 ms/op
     p(99.9990) =     12.370 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.438 ± 2.601  ops/ms
ClientPb.existUser                       thrpt       3  12.909 ± 2.212  ops/ms
ClientPb.getUser                         thrpt       3  12.686 ± 0.598  ops/ms
ClientPb.listUser                        thrpt       3  10.433 ± 0.934  ops/ms
ClientPb.createUser                       avgt       3   2.561 ± 0.566   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.146   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.298   ms/op
ClientPb.listUser                         avgt       3   3.041 ± 0.095   ms/op
ClientPb.createUser                     sample  370584   2.588 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.873           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.875           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  385097   2.490 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.729           ms/op
ClientPb.getUser                        sample  380236   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.568           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.340           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.516           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  315335   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.156           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.403           ms/op
