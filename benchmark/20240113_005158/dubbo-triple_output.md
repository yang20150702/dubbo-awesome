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
# Warmup Iteration   1: 5.371 ops/ms
# Warmup Iteration   2: 12.195 ops/ms
# Warmup Iteration   3: 12.269 ops/ms
Iteration   1: 12.769 ops/ms
Iteration   2: 12.777 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.715 ±(99.9%) 1.834 ops/ms [Average]
  (min, avg, max) = (12.599, 12.715, 12.777), stdev = 0.101
  CI (99.9%): [10.881, 14.550] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.427 ops/ms
# Warmup Iteration   2: 13.188 ops/ms
# Warmup Iteration   3: 13.067 ops/ms
Iteration   1: 13.124 ops/ms
Iteration   2: 13.227 ops/ms
Iteration   3: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.138 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (13.064, 13.138, 13.227), stdev = 0.082
  CI (99.9%): [11.634, 14.642] (assumes normal distribution)


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
# Warmup Iteration   1: 8.021 ops/ms
# Warmup Iteration   2: 12.290 ops/ms
# Warmup Iteration   3: 12.777 ops/ms
Iteration   1: 12.836 ops/ms
Iteration   2: 12.877 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.850 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (12.836, 12.850, 12.877), stdev = 0.023
  CI (99.9%): [12.429, 13.272] (assumes normal distribution)


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
# Warmup Iteration   1: 6.854 ops/ms
# Warmup Iteration   2: 10.441 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.705 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (10.635, 10.705, 10.741), stdev = 0.061
  CI (99.9%): [9.596, 11.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.561 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.539 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.522, 2.539, 2.561), stdev = 0.020
  CI (99.9%): [2.178, 2.901] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.438, 2.443, 2.451), stdev = 0.007
  CI (99.9%): [2.324, 2.562] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.003 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.475, 2.490, 2.504), stdev = 0.014
  CI (99.9%): [2.231, 2.749] (assumes normal distribution)


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.005 ms/op
Iteration   1: 2.966 ±(99.9%) 0.006 ms/op
Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
Iteration   3: 2.968 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.966 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (2.964, 2.966, 2.968), stdev = 0.002
  CI (99.9%): [2.929, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  6.283 ms/op
                 createUser·p0.9999: 11.682 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   4.015 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 10.720 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388868
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 189326 
    [ 2.500,  3.750) = 195640 
    [ 3.750,  5.000) = 3084 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      8.482 ms/op
     p(99.9900) =     13.257 ms/op
     p(99.9990) =     14.522 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  8.029 ms/op
                 existUser·p0.9999: 13.683 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.588 ms/op
                 existUser·p0.9999: 13.351 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  8.408 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393125
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 193252 
    [ 2.500,  3.750) = 196872 
    [ 3.750,  5.000) = 2042 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.945 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  9.959 ms/op
                 getUser·p0.9999: 13.864 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  8.583 ms/op
                 getUser·p0.9999: 11.834 ms/op
                 getUser·p1.00:   12.878 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  7.914 ms/op
                 getUser·p0.9999: 12.390 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384394
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 190283 
    [ 2.500,  3.750) = 189765 
    [ 3.750,  5.000) = 3569 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      7.650 ms/op
     p(99.9900) =     13.215 ms/op
     p(99.9990) =     14.997 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
Iteration   1: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.418 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 9.912 ms/op
                 listUser·p1.00:   10.797 ms/op

Iteration   2: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.124 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.837 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322241
  mean =      2.977 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 99300 
    [ 2.500,  3.750) = 184811 
    [ 3.750,  5.000) = 31049 
    [ 5.000,  6.250) = 5751 
    [ 6.250,  7.500) = 495 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.727 ms/op
     p(99.9990) =     12.399 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.715 ± 1.834  ops/ms
ClientPb.existUser                       thrpt       3  13.138 ± 1.504  ops/ms
ClientPb.getUser                         thrpt       3  12.850 ± 0.421  ops/ms
ClientPb.listUser                        thrpt       3  10.705 ± 1.108  ops/ms
ClientPb.createUser                       avgt       3   2.539 ± 0.361   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.119   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.259   ms/op
ClientPb.listUser                         avgt       3   2.966 ± 0.037   ms/op
ClientPb.createUser                     sample  388868   2.466 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.482           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.257           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.843           ms/op
ClientPb.existUser                      sample  393125   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.176           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  384394   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.972           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.650           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.215           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.303           ms/op
ClientPb.listUser                       sample  322241   2.977 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.741           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.727           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
