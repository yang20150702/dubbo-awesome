# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.932 ops/ms
# Warmup Iteration   2: 4.840 ops/ms
# Warmup Iteration   3: 8.568 ops/ms
Iteration   1: 8.963 ops/ms
Iteration   2: 9.461 ops/ms
Iteration   3: 9.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.147 ±(99.9%) 4.974 ops/ms [Average]
  (min, avg, max) = (8.963, 9.147, 9.461), stdev = 0.273
  CI (99.9%): [4.173, 14.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 8.333 ops/ms
# Warmup Iteration   3: 9.318 ops/ms
Iteration   1: 9.172 ops/ms
Iteration   2: 9.605 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.417 ±(99.9%) 4.045 ops/ms [Average]
  (min, avg, max) = (9.172, 9.417, 9.605), stdev = 0.222
  CI (99.9%): [5.372, 13.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 8.087 ops/ms
# Warmup Iteration   3: 8.724 ops/ms
Iteration   1: 9.111 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.252 ±(99.9%) 4.273 ops/ms [Average]
  (min, avg, max) = (9.111, 9.252, 9.522), stdev = 0.234
  CI (99.9%): [4.979, 13.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 7.056 ops/ms
# Warmup Iteration   3: 7.543 ops/ms
Iteration   1: 7.524 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.751 ±(99.9%) 3.903 ops/ms [Average]
  (min, avg, max) = (7.524, 7.751, 7.949), stdev = 0.214
  CI (99.9%): [3.848, 11.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.314 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.003 ms/op
Iteration   1: 3.421 ±(99.9%) 0.009 ms/op
Iteration   2: 3.348 ±(99.9%) 0.010 ms/op
Iteration   3: 3.436 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.401 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (3.348, 3.401, 3.436), stdev = 0.047
  CI (99.9%): [2.541, 4.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.834 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.003 ms/op
Iteration   1: 3.344 ±(99.9%) 0.011 ms/op
Iteration   2: 3.350 ±(99.9%) 0.005 ms/op
Iteration   3: 3.267 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.267, 3.320, 3.350), stdev = 0.047
  CI (99.9%): [2.468, 4.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.655 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.005 ms/op
Iteration   1: 3.334 ±(99.9%) 0.010 ms/op
Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
Iteration   3: 3.397 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.334, 3.380, 3.408), stdev = 0.040
  CI (99.9%): [2.651, 4.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.968 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.009 ms/op
Iteration   1: 3.951 ±(99.9%) 0.015 ms/op
Iteration   2: 4.149 ±(99.9%) 0.005 ms/op
Iteration   3: 3.846 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.982 ±(99.9%) 2.808 ms/op [Average]
  (min, avg, max) = (3.846, 3.982, 4.149), stdev = 0.154
  CI (99.9%): [1.174, 6.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.123 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.012 ms/op
Iteration   1: 3.696 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   6.537 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  26.673 ms/op
                 createUser·p0.9999: 29.884 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   2: 3.400 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  24.733 ms/op
                 createUser·p0.9999: 30.985 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   3: 3.374 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  25.395 ms/op
                 createUser·p0.9999: 43.057 ms/op
                 createUser·p1.00:   44.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275604
  mean =      3.484 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264371 
    [ 5.000, 10.000) = 10614 
    [10.000, 15.000) = 227 
    [15.000, 20.000) = 102 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 217 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     41.513 ms/op
     p(99.9990) =     43.844 ms/op
     p(99.9999) =     44.302 ms/op
    p(100.0000) =     44.302 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.798 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
Iteration   1: 3.350 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  10.367 ms/op
                 existUser·p0.9999: 24.329 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  19.529 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  22.059 ms/op
                 existUser·p0.9999: 27.363 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287710
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3488 
    [ 2.500,  5.000) = 277817 
    [ 5.000,  7.500) = 5476 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 99 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     11.506 ms/op
     p(99.9900) =     26.550 ms/op
     p(99.9990) =     28.189 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.961 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.011 ms/op
Iteration   1: 3.721 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  24.084 ms/op
                 getUser·p0.9999: 27.625 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   2: 3.488 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  23.577 ms/op
                 getUser·p0.9999: 28.208 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   3: 3.523 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  11.904 ms/op
                 getUser·p0.9999: 28.680 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268398
  mean =      3.574 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3979 
    [ 2.500,  5.000) = 254208 
    [ 5.000,  7.500) = 7998 
    [ 7.500, 10.000) = 1401 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 115 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     23.351 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.488 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.289 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.682 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.322 ±(99.9%) 0.016 ms/op
Iteration   1: 4.247 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.263 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  27.001 ms/op
                 listUser·p0.9999: 30.472 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 4.255 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  16.758 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.942 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 18.831 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231633
  mean =      4.143 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 217236 
    [ 5.000,  7.500) = 11322 
    [ 7.500, 10.000) = 2113 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.167 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.960 ms/op
     p(99.9000) =     18.034 ms/op
     p(99.9900) =     29.535 ms/op
     p(99.9990) =     31.941 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.147 ± 4.974  ops/ms
ClientPb.existUser                       thrpt       3   9.417 ± 4.045  ops/ms
ClientPb.getUser                         thrpt       3   9.252 ± 4.273  ops/ms
ClientPb.listUser                        thrpt       3   7.751 ± 3.903  ops/ms
ClientPb.createUser                       avgt       3   3.401 ± 0.860   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 0.852   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.728   ms/op
ClientPb.listUser                         avgt       3   3.982 ± 2.808   ms/op
ClientPb.createUser                     sample  275604   3.484 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.311           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.395           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.513           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.302           ms/op
ClientPb.existUser                      sample  287710   3.335 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.506           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  268398   3.574 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.351           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.951           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  231633   4.143 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.034           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.535           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.342           ms/op
