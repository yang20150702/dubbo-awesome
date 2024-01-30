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
# Warmup Iteration   1: 4.718 ops/ms
# Warmup Iteration   2: 12.284 ops/ms
# Warmup Iteration   3: 12.462 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.768 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (12.700, 12.768, 12.898), stdev = 0.113
  CI (99.9%): [10.706, 14.829] (assumes normal distribution)


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
# Warmup Iteration   1: 7.916 ops/ms
# Warmup Iteration   2: 13.230 ops/ms
# Warmup Iteration   3: 13.149 ops/ms
Iteration   1: 13.166 ops/ms
Iteration   2: 13.323 ops/ms
Iteration   3: 13.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.257 ±(99.9%) 1.478 ops/ms [Average]
  (min, avg, max) = (13.166, 13.257, 13.323), stdev = 0.081
  CI (99.9%): [11.778, 14.735] (assumes normal distribution)


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
# Warmup Iteration   1: 8.147 ops/ms
# Warmup Iteration   2: 12.518 ops/ms
# Warmup Iteration   3: 13.070 ops/ms
Iteration   1: 13.114 ops/ms
Iteration   2: 13.168 ops/ms
Iteration   3: 13.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.125 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (13.092, 13.125, 13.168), stdev = 0.039
  CI (99.9%): [12.406, 13.844] (assumes normal distribution)


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
# Warmup Iteration   1: 6.743 ops/ms
# Warmup Iteration   2: 10.561 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 10.825 ops/ms
Iteration   3: 10.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.778 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (10.728, 10.778, 10.825), stdev = 0.049
  CI (99.9%): [9.887, 11.670] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.003 ms/op
Iteration   2: 2.484 ±(99.9%) 0.003 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.484, 2.502, 2.521), stdev = 0.018
  CI (99.9%): [2.168, 2.837] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.004 ms/op
Iteration   1: 2.372 ±(99.9%) 0.003 ms/op
Iteration   2: 2.420 ±(99.9%) 0.003 ms/op
Iteration   3: 2.408 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.400 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (2.372, 2.400, 2.420), stdev = 0.025
  CI (99.9%): [1.946, 2.853] (assumes normal distribution)


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
# Warmup Iteration   1: 4.039 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.003 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.459, 2.468, 2.483), stdev = 0.013
  CI (99.9%): [2.230, 2.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.958 ±(99.9%) 0.004 ms/op
Iteration   3: 2.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.970 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.958, 2.970, 2.981), stdev = 0.012
  CI (99.9%): [2.760, 3.180] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  9.744 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.698 ms/op
                 createUser·p0.999:  7.047 ms/op
                 createUser·p0.9999: 11.736 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.923 ms/op
                 createUser·p0.999:  8.685 ms/op
                 createUser·p0.9999: 11.489 ms/op
                 createUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385690
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 188120 
    [ 2.500,  3.750) = 193617 
    [ 3.750,  5.000) = 2963 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     12.611 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  5.061 ms/op
                 existUser·p0.9999: 13.198 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.900 ms/op
                 existUser·p0.9999: 20.933 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 12.022 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395287
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196353 
    [ 2.500,  5.000) = 198270 
    [ 5.000,  7.500) = 308 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =      5.793 ms/op
     p(99.9900) =     13.328 ms/op
     p(99.9990) =     21.891 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  9.920 ms/op
                 getUser·p0.9999: 16.433 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  9.098 ms/op
                 getUser·p0.9999: 11.425 ms/op
                 getUser·p1.00:   11.993 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  7.179 ms/op
                 getUser·p0.9999: 12.517 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384403
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 190131 
    [ 2.500,  3.750) = 188259 
    [ 3.750,  5.000) = 4321 
    [ 5.000,  6.250) = 1124 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      8.218 ms/op
     p(99.9900) =     13.715 ms/op
     p(99.9990) =     17.405 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.008 ms/op
Iteration   1: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.556 ms/op
                 listUser·p0.999:  9.033 ms/op
                 listUser·p0.9999: 10.346 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   2: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.121 ms/op
                 listUser·p0.9999: 12.684 ms/op
                 listUser·p1.00:   13.222 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.879 ms/op
                 listUser·p0.9999: 12.124 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324054
  mean =      2.960 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 100532 
    [ 2.500,  3.750) = 187845 
    [ 3.750,  5.000) = 29102 
    [ 5.000,  6.250) = 5247 
    [ 6.250,  7.500) = 544 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     11.724 ms/op
     p(99.9990) =     13.087 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.768 ± 2.061  ops/ms
ClientPb.existUser                       thrpt       3  13.257 ± 1.478  ops/ms
ClientPb.getUser                         thrpt       3  13.125 ± 0.719  ops/ms
ClientPb.listUser                        thrpt       3  10.778 ± 0.892  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.334   ms/op
ClientPb.existUser                        avgt       3   2.400 ± 0.453   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   2.970 ± 0.210   ms/op
ClientPb.createUser                     sample  385690   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.716           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.611           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.041           ms/op
ClientPb.existUser                      sample  395287   2.426 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.328           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.675           ms/op
ClientPb.getUser                        sample  384403   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.933           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.715           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.531           ms/op
ClientPb.listUser                       sample  324054   2.960 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.856           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.724           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.222           ms/op
