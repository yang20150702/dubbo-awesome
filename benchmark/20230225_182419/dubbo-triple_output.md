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
# Warmup Iteration   1: 2.735 ops/ms
# Warmup Iteration   2: 6.207 ops/ms
# Warmup Iteration   3: 9.685 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 9.940 ops/ms
Iteration   3: 10.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.005 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (9.940, 10.005, 10.058), stdev = 0.060
  CI (99.9%): [8.912, 11.097] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ops/ms
# Warmup Iteration   2: 9.521 ops/ms
# Warmup Iteration   3: 10.336 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.690 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.609 ±(99.9%) 1.460 ops/ms [Average]
  (min, avg, max) = (10.530, 10.609, 10.690), stdev = 0.080
  CI (99.9%): [9.149, 12.069] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.658 ops/ms
# Warmup Iteration   2: 9.559 ops/ms
# Warmup Iteration   3: 9.765 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.060 ops/ms
Iteration   3: 9.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.981 ±(99.9%) 1.462 ops/ms [Average]
  (min, avg, max) = (9.900, 9.981, 10.060), stdev = 0.080
  CI (99.9%): [8.518, 11.443] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.328 ops/ms
# Warmup Iteration   2: 7.649 ops/ms
# Warmup Iteration   3: 8.623 ops/ms
Iteration   1: 8.567 ops/ms
Iteration   2: 8.629 ops/ms
Iteration   3: 8.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.586 ±(99.9%) 0.682 ops/ms [Average]
  (min, avg, max) = (8.562, 8.586, 8.629), stdev = 0.037
  CI (99.9%): [7.904, 9.268] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.552 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.005 ms/op
Iteration   1: 3.212 ±(99.9%) 0.005 ms/op
Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
Iteration   3: 3.118 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.147 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.111, 3.147, 3.212), stdev = 0.057
  CI (99.9%): [2.116, 4.178] (assumes normal distribution)


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
# Warmup Iteration   1: 7.233 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.001 ms/op
Iteration   1: 3.140 ±(99.9%) 0.003 ms/op
Iteration   2: 2.988 ±(99.9%) 0.007 ms/op
Iteration   3: 3.166 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.098 ±(99.9%) 1.760 ms/op [Average]
  (min, avg, max) = (2.988, 3.098, 3.166), stdev = 0.096
  CI (99.9%): [1.338, 4.858] (assumes normal distribution)


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
# Warmup Iteration   1: 7.581 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.006 ms/op
Iteration   1: 3.236 ±(99.9%) 0.006 ms/op
Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
Iteration   3: 3.147 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.168 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.120, 3.168, 3.236), stdev = 0.061
  CI (99.9%): [2.062, 4.273] (assumes normal distribution)


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
# Warmup Iteration   1: 8.732 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.008 ms/op
Iteration   1: 3.650 ±(99.9%) 0.012 ms/op
Iteration   2: 3.835 ±(99.9%) 0.005 ms/op
Iteration   3: 3.707 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.731 ±(99.9%) 1.734 ms/op [Average]
  (min, avg, max) = (3.650, 3.731, 3.835), stdev = 0.095
  CI (99.9%): [1.996, 5.465] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.773 ms/op
                 createUser·p0.999:  13.844 ms/op
                 createUser·p0.9999: 18.483 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.449 ms/op
                 createUser·p0.99:   5.209 ms/op
                 createUser·p0.999:  17.100 ms/op
                 createUser·p0.9999: 22.965 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.530 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.375 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  15.138 ms/op
                 createUser·p0.9999: 17.750 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304097
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27402 
    [ 2.500,  5.000) = 271693 
    [ 5.000,  7.500) = 4116 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.219 ms/op
     p(99.9900) =     21.559 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.321 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 19.740 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 25.267 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  13.222 ms/op
                 existUser·p0.9999: 24.150 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309079
  mean =      3.106 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19587 
    [ 2.500,  5.000) = 284492 
    [ 5.000,  7.500) = 4143 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     24.779 ms/op
     p(99.9990) =     25.714 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 8.036 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.010 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  17.138 ms/op
                 getUser·p0.9999: 20.082 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.115 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  13.574 ms/op
                 getUser·p0.9999: 25.270 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   5.220 ms/op
                 getUser·p0.999:  10.936 ms/op
                 getUser·p0.9999: 22.106 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 307428
  mean =      3.122 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17654 
    [ 2.500,  5.000) = 283731 
    [ 5.000,  7.500) = 5143 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     23.848 ms/op
     p(99.9990) =     25.814 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 8.493 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
Iteration   1: 3.804 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 22.367 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.808 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.715 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.623 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.723 ms/op
                 listUser·p0.95:   4.006 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.568 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258328
  mean =      3.714 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 250414 
    [ 5.000,  7.500) = 5747 
    [ 7.500, 10.000) = 1258 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.101 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     22.558 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.005 ± 1.093  ops/ms
ClientPb.existUser                       thrpt       3  10.609 ± 1.460  ops/ms
ClientPb.getUser                         thrpt       3   9.981 ± 1.462  ops/ms
ClientPb.listUser                        thrpt       3   8.586 ± 0.682  ops/ms
ClientPb.createUser                       avgt       3   3.147 ± 1.031   ms/op
ClientPb.existUser                        avgt       3   3.098 ± 1.760   ms/op
ClientPb.getUser                          avgt       3   3.168 ± 1.105   ms/op
ClientPb.listUser                         avgt       3   3.731 ± 1.734   ms/op
ClientPb.createUser                     sample  304097   3.155 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.219           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.559           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  309079   3.106 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.736           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.779           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.214           ms/op
ClientPb.getUser                        sample  307428   3.122 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.548           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.848           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  258328   3.714 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.423           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.101           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.775           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.675           ms/op
