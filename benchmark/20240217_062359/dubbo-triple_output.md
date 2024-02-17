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
# Warmup Iteration   1: 5.200 ops/ms
# Warmup Iteration   2: 11.997 ops/ms
# Warmup Iteration   3: 12.417 ops/ms
Iteration   1: 12.740 ops/ms
Iteration   2: 12.705 ops/ms
Iteration   3: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.773 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (12.705, 12.773, 12.874), stdev = 0.089
  CI (99.9%): [11.148, 14.398] (assumes normal distribution)


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
# Warmup Iteration   1: 8.537 ops/ms
# Warmup Iteration   2: 13.340 ops/ms
# Warmup Iteration   3: 13.398 ops/ms
Iteration   1: 13.381 ops/ms
Iteration   2: 13.142 ops/ms
Iteration   3: 13.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.243 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (13.142, 13.243, 13.381), stdev = 0.124
  CI (99.9%): [10.985, 15.502] (assumes normal distribution)


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
# Warmup Iteration   1: 7.690 ops/ms
# Warmup Iteration   2: 12.725 ops/ms
# Warmup Iteration   3: 13.047 ops/ms
Iteration   1: 13.027 ops/ms
Iteration   2: 13.101 ops/ms
Iteration   3: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.037 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (12.984, 13.037, 13.101), stdev = 0.059
  CI (99.9%): [11.955, 14.119] (assumes normal distribution)


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
# Warmup Iteration   1: 6.931 ops/ms
# Warmup Iteration   2: 10.778 ops/ms
# Warmup Iteration   3: 10.800 ops/ms
Iteration   1: 10.736 ops/ms
Iteration   2: 10.721 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.724 ±(99.9%) 0.200 ops/ms [Average]
  (min, avg, max) = (10.715, 10.724, 10.736), stdev = 0.011
  CI (99.9%): [10.524, 10.924] (assumes normal distribution)


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (2.530, 2.532, 2.537), stdev = 0.004
  CI (99.9%): [2.459, 2.605] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.003 ms/op
Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.416, 2.427, 2.445), stdev = 0.015
  CI (99.9%): [2.145, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (2.468, 2.485, 2.517), stdev = 0.028
  CI (99.9%): [1.968, 3.002] (assumes normal distribution)


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.972, 2.978, 2.987), stdev = 0.008
  CI (99.9%): [2.835, 3.120] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.864 ms/op
                 createUser·p0.999:  11.143 ms/op
                 createUser·p0.9999: 16.406 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 12.961 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  7.889 ms/op
                 createUser·p0.9999: 10.671 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380174
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 182814 
    [ 2.500,  3.750) = 193441 
    [ 3.750,  5.000) = 3011 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
Iteration   1: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  5.183 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.503 ms/op
                 existUser·p0.9999: 14.317 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  7.576 ms/op
                 existUser·p0.9999: 11.070 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400433
  mean =      2.395 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 207299 
    [ 2.500,  3.750) = 190747 
    [ 3.750,  5.000) = 1736 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.235 ms/op
     p(99.9900) =     12.876 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  11.240 ms/op
                 getUser·p0.9999: 13.166 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.453 ms/op
                 getUser·p0.9999: 13.029 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  8.276 ms/op
                 getUser·p0.9999: 11.747 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383432
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 189373 
    [ 2.500,  3.750) = 189530 
    [ 3.750,  5.000) = 3452 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.288 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     14.112 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.781 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.960 ms/op
                 listUser·p0.9999: 11.813 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.868 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.827 ms/op
                 listUser·p0.9999: 11.782 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318044
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 93200 
    [ 2.500,  3.750) = 185068 
    [ 3.750,  5.000) = 31849 
    [ 5.000,  6.250) = 6471 
    [ 6.250,  7.500) = 702 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 220 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     11.563 ms/op
     p(99.9990) =     12.807 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.773 ± 1.625  ops/ms
ClientPb.existUser                       thrpt       3  13.243 ± 2.258  ops/ms
ClientPb.getUser                         thrpt       3  13.037 ± 1.082  ops/ms
ClientPb.listUser                        thrpt       3  10.724 ± 0.200  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.073   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.282   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.517   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.143   ms/op
ClientPb.createUser                     sample  380174   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.581           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.582           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.170           ms/op
ClientPb.existUser                      sample  400433   2.395 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.235           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.876           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  383432   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.756           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.288           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.334           ms/op
ClientPb.listUser                       sample  318044   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.739           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.864           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.563           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
