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
# Warmup Iteration   1: 1.650 ops/ms
# Warmup Iteration   2: 3.853 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 7.700 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.111 ±(99.9%) 7.454 ops/ms [Average]
  (min, avg, max) = (7.700, 8.111, 8.517), stdev = 0.409
  CI (99.9%): [0.657, 15.565] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.409 ops/ms
# Warmup Iteration   2: 7.297 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 9.227 ops/ms
Iteration   2: 9.045 ops/ms
Iteration   3: 9.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.133 ±(99.9%) 1.660 ops/ms [Average]
  (min, avg, max) = (9.045, 9.133, 9.227), stdev = 0.091
  CI (99.9%): [7.473, 10.793] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.393 ops/ms
# Warmup Iteration   2: 6.968 ops/ms
# Warmup Iteration   3: 7.659 ops/ms
Iteration   1: 8.017 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 7.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.894 ±(99.9%) 10.209 ops/ms [Average]
  (min, avg, max) = (7.283, 7.894, 8.382), stdev = 0.560
  CI (99.9%): [≈ 0, 18.103] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.332 ops/ms
# Warmup Iteration   2: 5.966 ops/ms
# Warmup Iteration   3: 7.064 ops/ms
Iteration   1: 7.121 ops/ms
Iteration   2: 7.130 ops/ms
Iteration   3: 7.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.212 ±(99.9%) 2.713 ops/ms [Average]
  (min, avg, max) = (7.121, 7.212, 7.383), stdev = 0.149
  CI (99.9%): [4.499, 9.925] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.528 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.005 ms/op
Iteration   1: 3.645 ±(99.9%) 0.014 ms/op
Iteration   2: 3.788 ±(99.9%) 0.009 ms/op
Iteration   3: 3.765 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.733 ±(99.9%) 1.404 ms/op [Average]
  (min, avg, max) = (3.645, 3.733, 3.788), stdev = 0.077
  CI (99.9%): [2.329, 5.137] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.330 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.747 ±(99.9%) 0.006 ms/op
Iteration   2: 3.583 ±(99.9%) 0.006 ms/op
Iteration   3: 3.613 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.648 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.583, 3.648, 3.747), stdev = 0.087
  CI (99.9%): [2.054, 5.241] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.957 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.004 ms/op
Iteration   1: 3.946 ±(99.9%) 0.004 ms/op
Iteration   2: 3.704 ±(99.9%) 0.011 ms/op
Iteration   3: 3.633 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.761 ±(99.9%) 2.991 ms/op [Average]
  (min, avg, max) = (3.633, 3.761, 3.946), stdev = 0.164
  CI (99.9%): [0.770, 6.752] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.968 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.968 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.591 ±(99.9%) 0.008 ms/op
Iteration   1: 4.313 ±(99.9%) 0.012 ms/op
Iteration   2: 4.226 ±(99.9%) 0.014 ms/op
Iteration   3: 4.380 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.306 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (4.226, 4.306, 4.380), stdev = 0.077
  CI (99.9%): [2.898, 5.714] (assumes normal distribution)


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
# Warmup Iteration   1: 12.417 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.015 ms/op
Iteration   1: 3.744 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  20.073 ms/op
                 createUser·p0.9999: 23.671 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  22.372 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   3: 4.059 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.798 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  11.026 ms/op
                 createUser·p0.9999: 39.365 ms/op
                 createUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248957
  mean =      3.856 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 239028 
    [ 5.000, 10.000) = 9448 
    [10.000, 15.000) = 223 
    [15.000, 20.000) = 11 
    [20.000, 25.000) = 153 
    [25.000, 30.000) = 62 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     19.957 ms/op
     p(99.9900) =     37.493 ms/op
     p(99.9990) =     40.240 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.338 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.012 ms/op
Iteration   1: 3.518 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  21.801 ms/op
                 existUser·p0.9999: 26.897 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 3.706 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  17.813 ms/op
                 existUser·p0.9999: 25.964 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 3.645 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.025 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  26.032 ms/op
                 existUser·p0.9999: 32.888 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265049
  mean =      3.621 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2409 
    [ 2.500,  5.000) = 256828 
    [ 5.000,  7.500) = 4669 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     31.244 ms/op
     p(99.9990) =     34.429 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.829 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.015 ms/op
Iteration   1: 3.912 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  15.598 ms/op
                 getUser·p0.9999: 26.858 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 3.699 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  23.117 ms/op
                 getUser·p0.9999: 26.653 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 3.801 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  25.229 ms/op
                 getUser·p0.9999: 31.168 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 252325
  mean =      3.802 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1060 
    [ 2.500,  5.000) = 241337 
    [ 5.000,  7.500) = 7740 
    [ 7.500, 10.000) = 1399 
    [10.000, 12.500) = 417 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     22.273 ms/op
     p(99.9900) =     28.140 ms/op
     p(99.9990) =     32.095 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.226 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.016 ms/op
Iteration   1: 4.693 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  23.167 ms/op
                 listUser·p0.9999: 25.270 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.565 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.467 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  16.244 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209628
  mean =      4.573 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 189987 
    [ 5.000,  7.500) = 15399 
    [ 7.500, 10.000) = 3043 
    [10.000, 12.500) = 562 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     18.559 ms/op
     p(99.9900) =     24.184 ms/op
     p(99.9990) =     25.704 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.111 ±  7.454  ops/ms
ClientPb.existUser                       thrpt       3   9.133 ±  1.660  ops/ms
ClientPb.getUser                         thrpt       3   7.894 ± 10.209  ops/ms
ClientPb.listUser                        thrpt       3   7.212 ±  2.713  ops/ms
ClientPb.createUser                       avgt       3   3.733 ±  1.404   ms/op
ClientPb.existUser                        avgt       3   3.648 ±  1.593   ms/op
ClientPb.getUser                          avgt       3   3.761 ±  2.991   ms/op
ClientPb.listUser                         avgt       3   4.306 ±  1.408   ms/op
ClientPb.createUser                     sample  248957   3.856 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.690            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.874            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.586            ms/op
ClientPb.createUser:createUser·p0.999   sample          19.957            ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.493            ms/op
ClientPb.createUser:createUser·p1.00    sample          40.370            ms/op
ClientPb.existUser                      sample  265049   3.621 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.499            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.580            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.973            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.308            ms/op
ClientPb.existUser:existUser·p0.999     sample          19.235            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.244            ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931            ms/op
ClientPb.getUser                        sample  252325   3.802 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.536            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.682            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.284            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.719            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168            ms/op
ClientPb.getUser:getUser·p0.999         sample          22.273            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.140            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342            ms/op
ClientPb.listUser                       sample  209628   4.573 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.741            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.415            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.973            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.431            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.559            ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.184            ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788            ms/op
