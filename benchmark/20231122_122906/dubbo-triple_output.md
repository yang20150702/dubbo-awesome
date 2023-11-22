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
# Warmup Iteration   1: 4.968 ops/ms
# Warmup Iteration   2: 12.195 ops/ms
# Warmup Iteration   3: 12.520 ops/ms
Iteration   1: 12.774 ops/ms
Iteration   2: 12.917 ops/ms
Iteration   3: 12.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.873 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (12.774, 12.873, 12.926), stdev = 0.086
  CI (99.9%): [11.312, 14.433] (assumes normal distribution)


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
# Warmup Iteration   1: 8.298 ops/ms
# Warmup Iteration   2: 13.086 ops/ms
# Warmup Iteration   3: 13.009 ops/ms
Iteration   1: 13.158 ops/ms
Iteration   2: 13.127 ops/ms
Iteration   3: 13.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.117 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (13.066, 13.117, 13.158), stdev = 0.047
  CI (99.9%): [12.263, 13.971] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ops/ms
# Warmup Iteration   2: 12.695 ops/ms
# Warmup Iteration   3: 12.975 ops/ms
Iteration   1: 12.976 ops/ms
Iteration   2: 13.032 ops/ms
Iteration   3: 13.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.029 ±(99.9%) 0.926 ops/ms [Average]
  (min, avg, max) = (12.976, 13.029, 13.078), stdev = 0.051
  CI (99.9%): [12.103, 13.954] (assumes normal distribution)


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
# Warmup Iteration   1: 6.695 ops/ms
# Warmup Iteration   2: 10.465 ops/ms
# Warmup Iteration   3: 10.742 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.716 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (10.658, 10.716, 10.764), stdev = 0.054
  CI (99.9%): [9.729, 11.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.003 ms/op
Iteration   1: 2.537 ±(99.9%) 0.003 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.513, 2.523, 2.537), stdev = 0.012
  CI (99.9%): [2.295, 2.751] (assumes normal distribution)


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.413 ±(99.9%) 0.005 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.412, 2.420, 2.436), stdev = 0.013
  CI (99.9%): [2.174, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.468, 2.503, 2.536), stdev = 0.034
  CI (99.9%): [1.879, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.006 ms/op
Iteration   2: 2.941 ±(99.9%) 0.004 ms/op
Iteration   3: 2.965 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.941, 2.951, 2.965), stdev = 0.012
  CI (99.9%): [2.728, 3.174] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  6.313 ms/op
                 createUser·p0.9999: 14.059 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   4.295 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 12.190 ms/op
                 createUser·p1.00:   12.517 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  7.546 ms/op
                 createUser·p0.9999: 11.244 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384396
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 186461 
    [ 2.500,  3.750) = 193192 
    [ 3.750,  5.000) = 3714 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      9.119 ms/op
     p(99.9900) =     13.510 ms/op
     p(99.9990) =     14.606 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.959 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  6.932 ms/op
                 existUser·p0.9999: 13.908 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  7.622 ms/op
                 existUser·p0.9999: 11.780 ms/op
                 existUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394513
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 197045 
    [ 2.500,  3.750) = 194493 
    [ 3.750,  5.000) = 2162 
    [ 5.000,  6.250) = 289 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.959 ms/op
     p(99.9900) =     13.675 ms/op
     p(99.9990) =     14.440 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  7.651 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  8.589 ms/op
                 getUser·p0.9999: 11.667 ms/op
                 getUser·p1.00:   12.468 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  5.382 ms/op
                 getUser·p0.9999: 10.479 ms/op
                 getUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389345
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 194486 
    [ 2.500,  3.750) = 189444 
    [ 3.750,  5.000) = 3588 
    [ 5.000,  6.250) = 1216 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.041 ms/op
     p(99.9000) =      8.001 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.904 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
Iteration   1: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.765 ms/op
                 listUser·p0.9999: 10.460 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 14.909 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 2.938 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.543 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 13.946 ms/op
                 listUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325044
  mean =      2.951 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 103944 
    [ 2.500,  3.750) = 184559 
    [ 3.750,  5.000) = 29512 
    [ 5.000,  6.250) = 5562 
    [ 6.250,  7.500) = 632 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     15.593 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.873 ± 1.560  ops/ms
ClientPb.existUser                       thrpt       3  13.117 ± 0.854  ops/ms
ClientPb.getUser                         thrpt       3  13.029 ± 0.926  ops/ms
ClientPb.listUser                        thrpt       3  10.716 ± 0.988  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.228   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.246   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.624   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.223   ms/op
ClientPb.createUser                     sample  384396   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.119           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.510           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  394513   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.802           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.675           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  389345   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.041           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.001           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.140           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  325044   2.951 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.320           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.499           ms/op
