# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.159 ops/ms
# Warmup Iteration   2: 2.602 ops/ms
# Warmup Iteration   3: 5.362 ops/ms
Iteration   1: 5.368 ops/ms
Iteration   2: 5.643 ops/ms
Iteration   3: 5.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.623 ±(99.9%) 4.487 ops/ms [Average]
  (min, avg, max) = (5.368, 5.623, 5.858), stdev = 0.246
  CI (99.9%): [1.136, 10.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 4.806 ops/ms
# Warmup Iteration   3: 5.669 ops/ms
Iteration   1: 5.543 ops/ms
Iteration   2: 5.491 ops/ms
Iteration   3: 5.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.481 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (5.409, 5.481, 5.543), stdev = 0.067
  CI (99.9%): [4.251, 6.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.277 ops/ms
# Warmup Iteration   2: 4.034 ops/ms
# Warmup Iteration   3: 5.658 ops/ms
Iteration   1: 5.529 ops/ms
Iteration   2: 5.509 ops/ms
Iteration   3: 5.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.644 ±(99.9%) 3.954 ops/ms [Average]
  (min, avg, max) = (5.509, 5.644, 5.894), stdev = 0.217
  CI (99.9%): [1.690, 9.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 3.773 ops/ms
# Warmup Iteration   3: 4.642 ops/ms
Iteration   1: 4.977 ops/ms
Iteration   2: 5.017 ops/ms
Iteration   3: 5.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.031 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (4.977, 5.031, 5.101), stdev = 0.063
  CI (99.9%): [3.875, 6.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.016 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 7.240 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.967 ±(99.9%) 0.009 ms/op
Iteration   1: 5.907 ±(99.9%) 0.007 ms/op
Iteration   2: 5.854 ±(99.9%) 0.011 ms/op
Iteration   3: 5.634 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.798 ±(99.9%) 2.647 ms/op [Average]
  (min, avg, max) = (5.634, 5.798, 5.907), stdev = 0.145
  CI (99.9%): [3.151, 8.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.187 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.430 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.575 ±(99.9%) 0.006 ms/op
Iteration   1: 5.221 ±(99.9%) 0.012 ms/op
Iteration   2: 5.251 ±(99.9%) 0.009 ms/op
Iteration   3: 5.253 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.242 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (5.221, 5.242, 5.253), stdev = 0.018
  CI (99.9%): [4.912, 5.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.613 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.674 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.703 ±(99.9%) 0.010 ms/op
Iteration   1: 5.640 ±(99.9%) 0.007 ms/op
Iteration   2: 5.692 ±(99.9%) 0.009 ms/op
Iteration   3: 5.376 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.569 ±(99.9%) 3.095 ms/op [Average]
  (min, avg, max) = (5.376, 5.569, 5.692), stdev = 0.170
  CI (99.9%): [2.474, 8.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.857 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 8.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.852 ±(99.9%) 0.007 ms/op
Iteration   1: 6.600 ±(99.9%) 0.015 ms/op
Iteration   2: 6.579 ±(99.9%) 0.014 ms/op
Iteration   3: 6.527 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.569 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (6.527, 6.569, 6.600), stdev = 0.038
  CI (99.9%): [5.881, 7.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.028 ±(99.9%) 0.393 ms/op
# Warmup Iteration   2: 7.238 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.791 ±(99.9%) 0.026 ms/op
Iteration   1: 5.522 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  26.707 ms/op
                 createUser·p0.9999: 41.393 ms/op
                 createUser·p1.00:   42.074 ms/op

Iteration   2: 5.470 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.701 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  28.213 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   3: 5.735 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.060 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   12.160 ms/op
                 createUser·p0.999:  30.514 ms/op
                 createUser·p0.9999: 34.893 ms/op
                 createUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172195
  mean =      5.573 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60712 
    [ 5.000, 10.000) = 109326 
    [10.000, 15.000) = 1658 
    [15.000, 20.000) = 180 
    [20.000, 25.000) = 71 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 124 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.913 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     28.574 ms/op
     p(99.9900) =     34.720 ms/op
     p(99.9990) =     41.932 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.334 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.266 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.019 ms/op
Iteration   1: 5.575 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.824 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  25.810 ms/op
                 existUser·p0.9999: 28.451 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 5.518 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   11.329 ms/op
                 existUser·p0.999:  26.838 ms/op
                 existUser·p0.9999: 29.433 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 5.405 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  28.436 ms/op
                 existUser·p0.9999: 31.427 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174531
  mean =      5.498 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 67059 
    [ 5.000,  7.500) = 96996 
    [ 7.500, 10.000) = 7842 
    [10.000, 12.500) = 1548 
    [12.500, 15.000) = 568 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     11.119 ms/op
     p(99.9000) =     26.212 ms/op
     p(99.9900) =     30.641 ms/op
     p(99.9990) =     32.129 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.599 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 7.037 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.804 ±(99.9%) 0.024 ms/op
Iteration   1: 5.732 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.695 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.955 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   13.435 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 5.681 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.070 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   11.603 ms/op
                 getUser·p0.999:  29.974 ms/op
                 getUser·p0.9999: 34.504 ms/op
                 getUser·p1.00:   34.865 ms/op

Iteration   3: 5.682 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.691 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   7.094 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  24.960 ms/op
                 getUser·p0.9999: 34.300 ms/op
                 getUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168354
  mean =      5.698 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 54258 
    [ 5.000,  7.500) = 101625 
    [ 7.500, 10.000) = 8848 
    [10.000, 12.500) = 2086 
    [12.500, 15.000) = 856 
    [15.000, 17.500) = 309 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.053 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     21.946 ms/op
     p(99.9900) =     33.827 ms/op
     p(99.9990) =     36.126 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.200 ±(99.9%) 0.404 ms/op
# Warmup Iteration   2: 8.840 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.618 ±(99.9%) 0.028 ms/op
Iteration   1: 6.663 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.695 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   10.125 ms/op
                 listUser·p0.99:   14.156 ms/op
                 listUser·p0.999:  26.967 ms/op
                 listUser·p0.9999: 30.192 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 6.439 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   13.433 ms/op
                 listUser·p0.999:  29.206 ms/op
                 listUser·p0.9999: 31.396 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   3: 6.484 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  22.434 ms/op
                 listUser·p0.9999: 28.721 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147104
  mean =      6.528 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 7209 
    [ 5.000,  7.500) = 118724 
    [ 7.500, 10.000) = 15136 
    [10.000, 12.500) = 4267 
    [12.500, 15.000) = 954 
    [15.000, 17.500) = 312 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.601 ms/op
     p(99.0000) =     13.124 ms/op
     p(99.9000) =     27.197 ms/op
     p(99.9900) =     30.811 ms/op
     p(99.9990) =     31.804 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.623 ± 4.487  ops/ms
ClientPb.existUser                       thrpt       3   5.481 ± 1.230  ops/ms
ClientPb.getUser                         thrpt       3   5.644 ± 3.954  ops/ms
ClientPb.listUser                        thrpt       3   5.031 ± 1.156  ops/ms
ClientPb.createUser                       avgt       3   5.798 ± 2.647   ms/op
ClientPb.existUser                        avgt       3   5.242 ± 0.329   ms/op
ClientPb.getUser                          avgt       3   5.569 ± 3.095   ms/op
ClientPb.listUser                         avgt       3   6.569 ± 0.688   ms/op
ClientPb.createUser                     sample  172195   5.573 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.799           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.643           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.584           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.574           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.720           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.074           ms/op
ClientPb.existUser                      sample  174531   5.498 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.499           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.767           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.782           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.119           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.212           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.641           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  168354   5.698 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.208           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.206           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.946           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.827           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.142           ms/op
ClientPb.listUser                       sample  147104   6.528 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.327           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.197           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.811           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.850           ms/op
