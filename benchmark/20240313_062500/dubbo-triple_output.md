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
# Warmup Iteration   1: 4.895 ops/ms
# Warmup Iteration   2: 12.163 ops/ms
# Warmup Iteration   3: 12.322 ops/ms
Iteration   1: 12.710 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 12.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.738 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (12.709, 12.738, 12.796), stdev = 0.050
  CI (99.9%): [11.823, 13.654] (assumes normal distribution)


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
# Warmup Iteration   1: 8.244 ops/ms
# Warmup Iteration   2: 13.254 ops/ms
# Warmup Iteration   3: 13.284 ops/ms
Iteration   1: 13.253 ops/ms
Iteration   2: 13.305 ops/ms
Iteration   3: 13.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.292 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (13.253, 13.292, 13.319), stdev = 0.035
  CI (99.9%): [12.655, 13.929] (assumes normal distribution)


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
# Warmup Iteration   1: 8.306 ops/ms
# Warmup Iteration   2: 13.173 ops/ms
# Warmup Iteration   3: 13.192 ops/ms
Iteration   1: 13.039 ops/ms
Iteration   2: 13.069 ops/ms
Iteration   3: 13.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.117 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (13.039, 13.117, 13.245), stdev = 0.111
  CI (99.9%): [11.087, 15.148] (assumes normal distribution)


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
# Warmup Iteration   1: 6.636 ops/ms
# Warmup Iteration   2: 10.667 ops/ms
# Warmup Iteration   3: 10.834 ops/ms
Iteration   1: 10.962 ops/ms
Iteration   2: 10.835 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.894 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (10.835, 10.894, 10.962), stdev = 0.064
  CI (99.9%): [9.722, 12.066] (assumes normal distribution)


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.463 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.448, 2.463, 2.476), stdev = 0.014
  CI (99.9%): [2.199, 2.727] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.388 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.373 ±(99.9%) 0.004 ms/op
Iteration   1: 2.375 ±(99.9%) 0.004 ms/op
Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
Iteration   3: 2.385 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.391 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (2.375, 2.391, 2.413), stdev = 0.020
  CI (99.9%): [2.035, 2.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.003 ms/op
Iteration   1: 2.438 ±(99.9%) 0.003 ms/op
Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
Iteration   3: 2.438 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.446 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.438, 2.446, 2.461), stdev = 0.013
  CI (99.9%): [2.206, 2.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.005 ms/op
Iteration   1: 2.936 ±(99.9%) 0.006 ms/op
Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
Iteration   3: 2.928 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.931 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.928, 2.931, 2.936), stdev = 0.005
  CI (99.9%): [2.845, 3.017] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  10.656 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  6.517 ms/op
                 createUser·p0.9999: 13.046 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.990 ms/op
                 createUser·p0.9999: 11.161 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385076
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 187234 
    [ 2.500,  3.750) = 193999 
    [ 3.750,  5.000) = 3090 
    [ 5.000,  6.250) = 219 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      8.976 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     14.444 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
Iteration   1: 2.391 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.797 ms/op
                 existUser·p0.9999: 13.118 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.406 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  6.503 ms/op
                 existUser·p0.9999: 13.360 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.757 ms/op
                 existUser·p0.999:  8.176 ms/op
                 existUser·p0.9999: 10.060 ms/op
                 existUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398558
  mean =      2.406 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 204974 
    [ 2.500,  3.750) = 190317 
    [ 3.750,  5.000) = 2388 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     12.962 ms/op
     p(99.9990) =     13.960 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  6.212 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  8.458 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  6.909 ms/op
                 getUser·p0.9999: 11.569 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388348
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 196960 
    [ 2.500,  3.750) = 186569 
    [ 3.750,  5.000) = 3651 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      7.656 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.176 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.654 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.009 ms/op
Iteration   1: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.566 ms/op
                 listUser·p0.9999: 10.653 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   2: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.447 ms/op
                 listUser·p0.999:  9.698 ms/op
                 listUser·p0.9999: 11.645 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.312 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323919
  mean =      2.961 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 101945 
    [ 2.500,  3.750) = 185285 
    [ 3.750,  5.000) = 29996 
    [ 5.000,  6.250) = 5368 
    [ 6.250,  7.500) = 596 
    [ 7.500,  8.750) = 216 
    [ 8.750, 10.000) = 201 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     12.362 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.738 ± 0.916  ops/ms
ClientPb.existUser                       thrpt       3  13.292 ± 0.637  ops/ms
ClientPb.getUser                         thrpt       3  13.117 ± 2.031  ops/ms
ClientPb.listUser                        thrpt       3  10.894 ± 1.172  ops/ms
ClientPb.createUser                       avgt       3   2.463 ± 0.264   ms/op
ClientPb.existUser                        avgt       3   2.391 ± 0.357   ms/op
ClientPb.getUser                          avgt       3   2.446 ± 0.240   ms/op
ClientPb.listUser                         avgt       3   2.931 ± 0.086   ms/op
ClientPb.createUser                     sample  385076   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.834           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.976           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.991           ms/op
ClientPb.existUser                      sample  398558   2.406 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.828           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.077           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.090           ms/op
ClientPb.getUser                        sample  388348   2.470 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.656           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  323919   2.961 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.744           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.943           ms/op
