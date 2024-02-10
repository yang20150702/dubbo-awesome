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
# Warmup Iteration   1: 4.903 ops/ms
# Warmup Iteration   2: 11.983 ops/ms
# Warmup Iteration   3: 12.462 ops/ms
Iteration   1: 12.712 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.718 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (12.642, 12.718, 12.799), stdev = 0.079
  CI (99.9%): [11.283, 14.152] (assumes normal distribution)


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
# Warmup Iteration   1: 8.202 ops/ms
# Warmup Iteration   2: 13.262 ops/ms
# Warmup Iteration   3: 13.057 ops/ms
Iteration   1: 13.189 ops/ms
Iteration   2: 13.144 ops/ms
Iteration   3: 13.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.119 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (13.024, 13.119, 13.189), stdev = 0.085
  CI (99.9%): [11.566, 14.672] (assumes normal distribution)


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
# Warmup Iteration   1: 7.976 ops/ms
# Warmup Iteration   2: 12.366 ops/ms
# Warmup Iteration   3: 12.626 ops/ms
Iteration   1: 12.745 ops/ms
Iteration   2: 12.724 ops/ms
Iteration   3: 12.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.681 ±(99.9%) 1.713 ops/ms [Average]
  (min, avg, max) = (12.573, 12.681, 12.745), stdev = 0.094
  CI (99.9%): [10.967, 14.394] (assumes normal distribution)


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
# Warmup Iteration   1: 6.860 ops/ms
# Warmup Iteration   2: 10.563 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.474 ops/ms
Iteration   2: 10.580 ops/ms
Iteration   3: 10.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.543 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (10.474, 10.543, 10.580), stdev = 0.060
  CI (99.9%): [9.455, 11.631] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (2.519, 2.529, 2.548), stdev = 0.016
  CI (99.9%): [2.236, 2.823] (assumes normal distribution)


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
# Warmup Iteration   1: 3.638 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
Iteration   2: 2.427 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.410, 2.426, 2.441), stdev = 0.015
  CI (99.9%): [2.151, 2.701] (assumes normal distribution)


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.480, 2.484, 2.489), stdev = 0.004
  CI (99.9%): [2.407, 2.562] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
Iteration   3: 2.983 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.974 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.968, 2.974, 2.983), stdev = 0.008
  CI (99.9%): [2.827, 3.121] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.287 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  8.501 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  7.032 ms/op
                 createUser·p0.9999: 12.326 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  8.617 ms/op
                 createUser·p0.9999: 10.928 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386132
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 187197 
    [ 2.500,  3.750) = 195880 
    [ 3.750,  5.000) = 2356 
    [ 5.000,  6.250) = 223 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      8.562 ms/op
     p(99.9900) =     13.146 ms/op
     p(99.9990) =     13.947 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.532 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.063 ms/op
                 existUser·p0.9999: 13.744 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  7.806 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  8.579 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390732
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 192662 
    [ 2.500,  3.750) = 195379 
    [ 3.750,  5.000) = 1940 
    [ 5.000,  6.250) = 254 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      7.856 ms/op
     p(99.9900) =     12.991 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  8.237 ms/op
                 getUser·p0.9999: 13.490 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 16.024 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  9.597 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382064
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 189008 
    [ 2.500,  3.750) = 188045 
    [ 3.750,  5.000) = 3585 
    [ 5.000,  6.250) = 911 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      9.600 ms/op
     p(99.9900) =     13.595 ms/op
     p(99.9990) =     16.478 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 4.890 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
Iteration   1: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 10.708 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   2: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.723 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313709
  mean =      3.057 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 78930 
    [ 2.500,  3.750) = 193769 
    [ 3.750,  5.000) = 33854 
    [ 5.000,  6.250) = 5770 
    [ 6.250,  7.500) = 638 
    [ 7.500,  8.750) = 174 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     11.020 ms/op
     p(99.9990) =     12.129 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.718 ± 1.435  ops/ms
ClientPb.existUser                       thrpt       3  13.119 ± 1.553  ops/ms
ClientPb.getUser                         thrpt       3  12.681 ± 1.713  ops/ms
ClientPb.listUser                        thrpt       3  10.543 ± 1.088  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.293   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.275   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.077   ms/op
ClientPb.listUser                         avgt       3   2.974 ± 0.147   ms/op
ClientPb.createUser                     sample  386132   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.908           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.621           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.562           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.146           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.025           ms/op
ClientPb.existUser                      sample  390732   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.916           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.856           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.991           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.762           ms/op
ClientPb.getUser                        sample  382064   2.510 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.600           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.595           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.613           ms/op
ClientPb.listUser                       sample  313709   3.057 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.020           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.632           ms/op
