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
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 12.006 ops/ms
# Warmup Iteration   3: 12.225 ops/ms
Iteration   1: 12.554 ops/ms
Iteration   2: 12.470 ops/ms
Iteration   3: 12.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.551 ±(99.9%) 1.442 ops/ms [Average]
  (min, avg, max) = (12.470, 12.551, 12.628), stdev = 0.079
  CI (99.9%): [11.109, 13.992] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.226 ops/ms
# Warmup Iteration   2: 12.996 ops/ms
# Warmup Iteration   3: 13.035 ops/ms
Iteration   1: 13.041 ops/ms
Iteration   2: 13.094 ops/ms
Iteration   3: 12.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.043 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (12.995, 13.043, 13.094), stdev = 0.050
  CI (99.9%): [12.140, 13.947] (assumes normal distribution)


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
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 12.310 ops/ms
# Warmup Iteration   3: 12.640 ops/ms
Iteration   1: 12.660 ops/ms
Iteration   2: 12.753 ops/ms
Iteration   3: 12.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.740 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (12.660, 12.740, 12.806), stdev = 0.074
  CI (99.9%): [11.396, 14.084] (assumes normal distribution)


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
# Warmup Iteration   1: 6.408 ops/ms
# Warmup Iteration   2: 10.443 ops/ms
# Warmup Iteration   3: 10.567 ops/ms
Iteration   1: 10.562 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.582 ±(99.9%) 0.467 ops/ms [Average]
  (min, avg, max) = (10.562, 10.582, 10.611), stdev = 0.026
  CI (99.9%): [10.114, 11.049] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.004 ms/op
Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (2.539, 2.559, 2.585), stdev = 0.023
  CI (99.9%): [2.132, 2.986] (assumes normal distribution)


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
# Warmup Iteration   1: 3.715 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.485 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.481, 2.485, 2.489), stdev = 0.004
  CI (99.9%): [2.413, 2.558] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.520 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (2.505, 2.520, 2.543), stdev = 0.020
  CI (99.9%): [2.158, 2.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.010 ms/op
Iteration   1: 2.966 ±(99.9%) 0.006 ms/op
Iteration   2: 2.992 ±(99.9%) 0.009 ms/op
Iteration   3: 2.980 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.966, 2.979, 2.992), stdev = 0.013
  CI (99.9%): [2.747, 3.211] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.721 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.687 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  12.714 ms/op
                 createUser·p0.9999: 21.860 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 2.525 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  10.437 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 2.574 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 14.935 ms/op
                 createUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369781
  mean =      2.594 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176896 
    [ 2.500,  5.000) = 190034 
    [ 5.000,  7.500) = 2024 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     10.437 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     22.259 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  11.869 ms/op
                 existUser·p0.9999: 14.598 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   2: 2.450 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  10.714 ms/op
                 existUser·p0.9999: 16.733 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 2.456 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.316 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.215 ms/op
                 existUser·p0.9999: 18.873 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388138
  mean =      2.471 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 210285 
    [ 2.500,  5.000) = 176097 
    [ 5.000,  7.500) = 1253 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      3.174 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      9.086 ms/op
     p(99.9900) =     17.254 ms/op
     p(99.9990) =     19.108 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.655 ±(99.9%) 0.008 ms/op
Iteration   1: 2.710 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.334 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  9.519 ms/op
                 getUser·p0.9999: 16.737 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   2: 2.600 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  12.338 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   3: 2.511 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.310 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.448 ms/op
                 getUser·p0.9999: 13.986 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368326
  mean =      2.604 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181309 
    [ 2.500,  5.000) = 183324 
    [ 5.000,  7.500) = 2977 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     16.089 ms/op
     p(99.9990) =     17.361 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.009 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.011 ms/op
Iteration   1: 3.060 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.388 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  10.560 ms/op
                 listUser·p0.9999: 18.204 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 2.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.708 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  12.331 ms/op
                 listUser·p0.9999: 15.726 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 2.956 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  10.715 ms/op
                 listUser·p0.9999: 12.242 ms/op
                 listUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320371
  mean =      2.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115757 
    [ 2.500,  5.000) = 194947 
    [ 5.000,  7.500) = 8560 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     10.922 ms/op
     p(99.9900) =     16.415 ms/op
     p(99.9990) =     18.769 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.551 ± 1.442  ops/ms
ClientPb.existUser                       thrpt       3  13.043 ± 0.903  ops/ms
ClientPb.getUser                         thrpt       3  12.740 ± 1.344  ops/ms
ClientPb.listUser                        thrpt       3  10.582 ± 0.467  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.427   ms/op
ClientPb.existUser                        avgt       3   2.485 ± 0.072   ms/op
ClientPb.getUser                          avgt       3   2.520 ± 0.363   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.232   ms/op
ClientPb.createUser                     sample  369781   2.594 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.391           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.437           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.137           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.413           ms/op
ClientPb.existUser                      sample  388138   2.471 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.316           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.429           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.086           ms/op
ClientPb.existUser:existUser·p0.9999    sample          17.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.480           ms/op
ClientPb.getUser                        sample  368326   2.604 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.334           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.699           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.089           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.021           ms/op
ClientPb.listUser                       sample  320371   2.994 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.388           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.964           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.922           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.415           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.054           ms/op
