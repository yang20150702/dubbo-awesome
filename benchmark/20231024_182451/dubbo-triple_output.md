# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.884 ops/ms
# Warmup Iteration   2: 1.923 ops/ms
# Warmup Iteration   3: 3.966 ops/ms
Iteration   1: 4.893 ops/ms
Iteration   2: 5.064 ops/ms
Iteration   3: 5.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.072 ±(99.9%) 3.349 ops/ms [Average]
  (min, avg, max) = (4.893, 5.072, 5.260), stdev = 0.184
  CI (99.9%): [1.723, 8.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.335 ops/ms
# Warmup Iteration   2: 3.638 ops/ms
# Warmup Iteration   3: 5.296 ops/ms
Iteration   1: 5.352 ops/ms
Iteration   2: 5.434 ops/ms
Iteration   3: 5.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.431 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (5.352, 5.431, 5.508), stdev = 0.078
  CI (99.9%): [4.013, 6.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.225 ops/ms
# Warmup Iteration   2: 3.495 ops/ms
# Warmup Iteration   3: 4.888 ops/ms
Iteration   1: 4.986 ops/ms
Iteration   2: 4.861 ops/ms
Iteration   3: 5.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.018 ±(99.9%) 3.194 ops/ms [Average]
  (min, avg, max) = (4.861, 5.018, 5.207), stdev = 0.175
  CI (99.9%): [1.824, 8.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.259 ops/ms
# Warmup Iteration   2: 3.258 ops/ms
# Warmup Iteration   3: 4.092 ops/ms
Iteration   1: 4.188 ops/ms
Iteration   2: 4.316 ops/ms
Iteration   3: 4.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.321 ±(99.9%) 2.484 ops/ms [Average]
  (min, avg, max) = (4.188, 4.321, 4.460), stdev = 0.136
  CI (99.9%): [1.837, 6.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.479 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 8.277 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.519 ±(99.9%) 0.013 ms/op
Iteration   1: 6.387 ±(99.9%) 0.013 ms/op
Iteration   2: 6.223 ±(99.9%) 0.012 ms/op
Iteration   3: 6.273 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.294 ±(99.9%) 1.535 ms/op [Average]
  (min, avg, max) = (6.223, 6.294, 6.387), stdev = 0.084
  CI (99.9%): [4.759, 7.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 22.103 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 7.747 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.955 ±(99.9%) 0.008 ms/op
Iteration   1: 6.161 ±(99.9%) 0.007 ms/op
Iteration   2: 5.982 ±(99.9%) 0.012 ms/op
Iteration   3: 5.903 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.015 ±(99.9%) 2.415 ms/op [Average]
  (min, avg, max) = (5.903, 6.015, 6.161), stdev = 0.132
  CI (99.9%): [3.601, 8.430] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.975 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 7.729 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.430 ±(99.9%) 0.010 ms/op
Iteration   1: 6.555 ±(99.9%) 0.006 ms/op
Iteration   2: 6.213 ±(99.9%) 0.009 ms/op
Iteration   3: 6.307 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.359 ±(99.9%) 3.226 ms/op [Average]
  (min, avg, max) = (6.213, 6.359, 6.555), stdev = 0.177
  CI (99.9%): [3.133, 9.584] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.457 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 9.394 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 7.558 ±(99.9%) 0.023 ms/op
Iteration   1: 7.410 ±(99.9%) 0.014 ms/op
Iteration   2: 7.207 ±(99.9%) 0.019 ms/op
Iteration   3: 7.180 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.266 ±(99.9%) 2.298 ms/op [Average]
  (min, avg, max) = (7.180, 7.266, 7.410), stdev = 0.126
  CI (99.9%): [4.968, 9.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.941 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 7.923 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.666 ±(99.9%) 0.036 ms/op
Iteration   1: 6.359 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   5.898 ms/op
                 createUser·p0.90:   8.520 ms/op
                 createUser·p0.95:   9.830 ms/op
                 createUser·p0.99:   13.582 ms/op
                 createUser·p0.999:  20.920 ms/op
                 createUser·p0.9999: 29.163 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 6.177 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   5.792 ms/op
                 createUser·p0.90:   7.873 ms/op
                 createUser·p0.95:   9.142 ms/op
                 createUser·p0.99:   12.747 ms/op
                 createUser·p0.999:  30.646 ms/op
                 createUser·p0.9999: 34.252 ms/op
                 createUser·p1.00:   35.717 ms/op

Iteration   3: 5.975 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.413 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.471 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   13.187 ms/op
                 createUser·p0.999:  31.620 ms/op
                 createUser·p0.9999: 43.123 ms/op
                 createUser·p1.00:   43.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 155565
  mean =      6.166 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 28833 
    [ 5.000, 10.000) = 121068 
    [10.000, 15.000) = 4893 
    [15.000, 20.000) = 496 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 91 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      7.946 ms/op
     p(95.0000) =      9.322 ms/op
     p(99.0000) =     13.260 ms/op
     p(99.9000) =     27.113 ms/op
     p(99.9900) =     41.681 ms/op
     p(99.9990) =     43.691 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.379 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 7.122 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.913 ±(99.9%) 0.025 ms/op
Iteration   1: 5.942 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.480 ms/op
                 existUser·p0.50:   5.415 ms/op
                 existUser·p0.90:   7.660 ms/op
                 existUser·p0.95:   9.339 ms/op
                 existUser·p0.99:   13.255 ms/op
                 existUser·p0.999:  33.568 ms/op
                 existUser·p0.9999: 37.527 ms/op
                 existUser·p1.00:   42.336 ms/op

Iteration   2: 5.633 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   7.119 ms/op
                 existUser·p0.95:   8.290 ms/op
                 existUser·p0.99:   11.620 ms/op
                 existUser·p0.999:  29.357 ms/op
                 existUser·p0.9999: 32.342 ms/op
                 existUser·p1.00:   33.292 ms/op

Iteration   3: 5.705 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.176 ms/op
                 existUser·p0.95:   8.307 ms/op
                 existUser·p0.99:   11.682 ms/op
                 existUser·p0.999:  18.592 ms/op
                 existUser·p0.9999: 38.297 ms/op
                 existUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 166608
  mean =      5.757 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 52443 
    [ 5.000, 10.000) = 109803 
    [10.000, 15.000) = 3715 
    [15.000, 20.000) = 406 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 19 
    [30.000, 35.000) = 92 
    [35.000, 40.000) = 53 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.480 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     25.814 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     41.158 ms/op
     p(99.9999) =     42.336 ms/op
    p(100.0000) =     42.336 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.513 ±(99.9%) 0.399 ms/op
# Warmup Iteration   2: 8.343 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 6.274 ±(99.9%) 0.027 ms/op
Iteration   1: 6.411 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.650 ms/op
                 getUser·p0.50:   5.931 ms/op
                 getUser·p0.90:   8.290 ms/op
                 getUser·p0.95:   9.732 ms/op
                 getUser·p0.99:   14.278 ms/op
                 getUser·p0.999:  28.326 ms/op
                 getUser·p0.9999: 31.359 ms/op
                 getUser·p1.00:   39.518 ms/op

Iteration   2: 6.260 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   5.726 ms/op
                 getUser·p0.90:   8.167 ms/op
                 getUser·p0.95:   9.732 ms/op
                 getUser·p0.99:   14.050 ms/op
                 getUser·p0.999:  29.781 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   3: 6.113 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.888 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   7.897 ms/op
                 getUser·p0.95:   9.355 ms/op
                 getUser·p0.99:   13.090 ms/op
                 getUser·p0.999:  19.857 ms/op
                 getUser·p0.9999: 40.879 ms/op
                 getUser·p1.00:   43.188 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 153303
  mean =      6.259 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 24327 
    [ 5.000, 10.000) = 122477 
    [10.000, 15.000) = 5457 
    [15.000, 20.000) = 772 
    [20.000, 25.000) = 70 
    [25.000, 30.000) = 90 
    [30.000, 35.000) = 74 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      5.759 ms/op
     p(90.0000) =      8.126 ms/op
     p(95.0000) =      9.634 ms/op
     p(99.0000) =     13.730 ms/op
     p(99.9000) =     27.538 ms/op
     p(99.9900) =     40.021 ms/op
     p(99.9990) =     42.909 ms/op
     p(99.9999) =     43.188 ms/op
    p(100.0000) =     43.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.675 ±(99.9%) 0.408 ms/op
# Warmup Iteration   2: 9.855 ±(99.9%) 0.084 ms/op
# Warmup Iteration   3: 7.283 ±(99.9%) 0.036 ms/op
Iteration   1: 7.145 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.582 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   9.175 ms/op
                 listUser·p0.95:   10.502 ms/op
                 listUser·p0.99:   14.114 ms/op
                 listUser·p0.999:  28.869 ms/op
                 listUser·p0.9999: 31.673 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   2: 7.165 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   14.235 ms/op
                 listUser·p0.999:  32.584 ms/op
                 listUser·p0.9999: 36.841 ms/op
                 listUser·p1.00:   38.404 ms/op

Iteration   3: 7.077 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   6.611 ms/op
                 listUser·p0.90:   8.946 ms/op
                 listUser·p0.95:   10.256 ms/op
                 listUser·p0.99:   14.437 ms/op
                 listUser·p0.999:  33.739 ms/op
                 listUser·p0.9999: 37.385 ms/op
                 listUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 134545
  mean =      7.129 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 1969 
    [ 5.000,  7.500) = 96258 
    [ 7.500, 10.000) = 28005 
    [10.000, 12.500) = 5719 
    [12.500, 15.000) = 1596 
    [15.000, 17.500) = 627 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 74 
    [32.500, 35.000) = 56 
    [35.000, 37.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      6.644 ms/op
     p(90.0000) =      9.044 ms/op
     p(95.0000) =     10.387 ms/op
     p(99.0000) =     14.238 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     36.700 ms/op
     p(99.9990) =     38.747 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.072 ± 3.349  ops/ms
ClientPb.existUser                       thrpt       3   5.431 ± 1.418  ops/ms
ClientPb.getUser                         thrpt       3   5.018 ± 3.194  ops/ms
ClientPb.listUser                        thrpt       3   4.321 ± 2.484  ops/ms
ClientPb.createUser                       avgt       3   6.294 ± 1.535   ms/op
ClientPb.existUser                        avgt       3   6.015 ± 2.415   ms/op
ClientPb.getUser                          avgt       3   6.359 ± 3.226   ms/op
ClientPb.listUser                         avgt       3   7.266 ± 2.298   ms/op
ClientPb.createUser                     sample  155565   6.166 ± 0.016   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.698           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.946           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.322           ms/op
ClientPb.createUser:createUser·p0.99    sample          13.260           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.113           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.909           ms/op
ClientPb.existUser                      sample  166608   5.757 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.480           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.569           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.255           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.814           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.421           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.336           ms/op
ClientPb.getUser                        sample  153303   6.259 ± 0.017   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.970           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.126           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.634           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.730           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.538           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.021           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.188           ms/op
ClientPb.listUser                       sample  134545   7.129 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.582           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.044           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.387           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.238           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.130           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.700           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.928           ms/op
