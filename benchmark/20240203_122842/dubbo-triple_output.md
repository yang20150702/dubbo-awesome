# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ops/ms
# Warmup Iteration   2: 11.823 ops/ms
# Warmup Iteration   3: 12.190 ops/ms
Iteration   1: 12.707 ops/ms
Iteration   2: 12.919 ops/ms
Iteration   3: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.785 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (12.707, 12.785, 12.919), stdev = 0.117
  CI (99.9%): [10.658, 14.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.012 ops/ms
# Warmup Iteration   2: 13.331 ops/ms
# Warmup Iteration   3: 13.118 ops/ms
Iteration   1: 13.720 ops/ms
Iteration   2: 13.464 ops/ms
Iteration   3: 13.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.490 ±(99.9%) 3.987 ops/ms [Average]
  (min, avg, max) = (13.285, 13.490, 13.720), stdev = 0.219
  CI (99.9%): [9.503, 17.476] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.656 ops/ms
# Warmup Iteration   2: 12.462 ops/ms
# Warmup Iteration   3: 13.139 ops/ms
Iteration   1: 12.924 ops/ms
Iteration   2: 13.132 ops/ms
Iteration   3: 13.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.047 ±(99.9%) 1.997 ops/ms [Average]
  (min, avg, max) = (12.924, 13.047, 13.132), stdev = 0.109
  CI (99.9%): [11.050, 15.044] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.439 ops/ms
# Warmup Iteration   2: 10.789 ops/ms
# Warmup Iteration   3: 11.085 ops/ms
Iteration   1: 11.101 ops/ms
Iteration   2: 11.020 ops/ms
Iteration   3: 11.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.083 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (11.020, 11.083, 11.128), stdev = 0.056
  CI (99.9%): [10.063, 12.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.476 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.463, 2.476, 2.486), stdev = 0.012
  CI (99.9%): [2.261, 2.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.386 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.365 ±(99.9%) 0.004 ms/op
Iteration   1: 2.373 ±(99.9%) 0.004 ms/op
Iteration   2: 2.356 ±(99.9%) 0.004 ms/op
Iteration   3: 2.352 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.360 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.352, 2.360, 2.373), stdev = 0.011
  CI (99.9%): [2.160, 2.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
Iteration   3: 2.387 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.406 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.387, 2.406, 2.417), stdev = 0.016
  CI (99.9%): [2.110, 2.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.103 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.005 ms/op
Iteration   1: 2.947 ±(99.9%) 0.004 ms/op
Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
Iteration   3: 2.931 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.934 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.924, 2.934, 2.947), stdev = 0.012
  CI (99.9%): [2.720, 3.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  10.465 ms/op
                 createUser·p0.9999: 15.099 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.577 ms/op
                 createUser·p0.50:   2.482 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.408 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.479 ms/op
                 createUser·p0.9999: 16.220 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.387 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.210 ms/op
                 createUser·p0.9999: 10.174 ms/op
                 createUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387397
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 390 
    [ 1.250,  2.500) = 197084 
    [ 2.500,  3.750) = 178807 
    [ 3.750,  5.000) = 9011 
    [ 5.000,  6.250) = 1449 
    [ 6.250,  7.500) = 147 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.432 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.207 ms/op
     p(99.9900) =     15.283 ms/op
     p(99.9990) =     16.880 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.354 ±(99.9%) 0.005 ms/op
Iteration   1: 2.353 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.372 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  7.801 ms/op
                 existUser·p0.9999: 9.703 ms/op
                 existUser·p1.00:   11.141 ms/op

Iteration   2: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.219 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.491 ms/op
                 existUser·p0.9999: 9.624 ms/op
                 existUser·p1.00:   10.420 ms/op

Iteration   3: 2.381 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.372 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  7.108 ms/op
                 existUser·p0.9999: 9.154 ms/op
                 existUser·p1.00:   10.519 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404776
  mean =      2.370 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 242136 
    [ 2.500,  3.750) = 153309 
    [ 3.750,  5.000) = 6581 
    [ 5.000,  6.250) = 1636 
    [ 6.250,  7.500) = 375 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 155 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.380 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.401 ms/op
     p(99.9900) =      9.610 ms/op
     p(99.9990) =     10.876 ms/op
     p(99.9999) =     11.141 ms/op
    p(100.0000) =     11.141 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.326 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.556 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.449 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  6.999 ms/op
                 getUser·p0.9999: 9.768 ms/op
                 getUser·p1.00:   10.486 ms/op

Iteration   2: 2.452 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.420 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.559 ms/op
                 getUser·p0.9999: 11.779 ms/op
                 getUser·p1.00:   12.108 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.404 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.439 ms/op
                 getUser·p0.9999: 9.614 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391860
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 604 
    [ 1.250,  2.500) = 213192 
    [ 2.500,  3.750) = 167244 
    [ 3.750,  5.000) = 8543 
    [ 5.000,  6.250) = 1678 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.400 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      6.825 ms/op
     p(99.9900) =     10.378 ms/op
     p(99.9990) =     12.030 ms/op
     p(99.9999) =     12.108 ms/op
    p(100.0000) =     12.108 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.22, OpenJDK 64-Bit Server VM, 11.0.22+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.008 ms/op
Iteration   1: 2.912 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  8.212 ms/op
                 listUser·p0.9999: 9.438 ms/op
                 listUser·p1.00:   10.633 ms/op

Iteration   2: 2.887 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.686 ms/op
                 listUser·p0.95:   4.092 ms/op
                 listUser·p0.99:   5.349 ms/op
                 listUser·p0.999:  7.278 ms/op
                 listUser·p0.9999: 8.944 ms/op
                 listUser·p1.00:   9.372 ms/op

Iteration   3: 2.913 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  7.447 ms/op
                 listUser·p0.9999: 9.443 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 330358
  mean =      2.904 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 215 
    [ 1.250,  2.500) = 103486 
    [ 2.500,  3.750) = 193963 
    [ 3.750,  5.000) = 26419 
    [ 5.000,  6.250) = 4700 
    [ 6.250,  7.500) = 1195 
    [ 7.500,  8.750) = 286 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =      9.289 ms/op
     p(99.9990) =     10.466 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.785 ± 2.127  ops/ms
ClientPb.existUser                       thrpt       3  13.490 ± 3.987  ops/ms
ClientPb.getUser                         thrpt       3  13.047 ± 1.997  ops/ms
ClientPb.listUser                        thrpt       3  11.083 ± 1.020  ops/ms
ClientPb.createUser                       avgt       3   2.476 ± 0.215   ms/op
ClientPb.existUser                        avgt       3   2.360 ± 0.201   ms/op
ClientPb.getUser                          avgt       3   2.406 ± 0.297   ms/op
ClientPb.listUser                         avgt       3   2.934 ± 0.214   ms/op
ClientPb.createUser                     sample  387397   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.577           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.486           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.207           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.283           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.252           ms/op
ClientPb.existUser                      sample  404776   2.370 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.657           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.380           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.401           ms/op
ClientPb.existUser:existUser·p0.9999    sample           9.610           ms/op
ClientPb.existUser:existUser·p1.00      sample          11.141           ms/op
ClientPb.getUser                        sample  391860   2.447 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.425           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.825           ms/op
ClientPb.getUser:getUser·p0.9999        sample          10.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          12.108           ms/op
ClientPb.listUser                       sample  330358   2.904 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.823           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           7.635           ms/op
ClientPb.listUser:listUser·p0.9999      sample           9.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.206           ms/op
