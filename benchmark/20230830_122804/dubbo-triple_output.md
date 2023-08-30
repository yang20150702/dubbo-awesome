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
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 6.468 ops/ms
# Warmup Iteration   3: 8.760 ops/ms
Iteration   1: 9.531 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.526 ±(99.9%) 0.480 ops/ms [Average]
  (min, avg, max) = (9.497, 9.526, 9.549), stdev = 0.026
  CI (99.9%): [9.046, 10.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ops/ms
# Warmup Iteration   2: 9.149 ops/ms
# Warmup Iteration   3: 9.637 ops/ms
Iteration   1: 10.566 ops/ms
Iteration   2: 10.228 ops/ms
Iteration   3: 9.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.247 ±(99.9%) 5.652 ops/ms [Average]
  (min, avg, max) = (9.947, 10.247, 10.566), stdev = 0.310
  CI (99.9%): [4.595, 15.900] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.858 ops/ms
# Warmup Iteration   2: 9.183 ops/ms
# Warmup Iteration   3: 9.572 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 9.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.817 ±(99.9%) 0.752 ops/ms [Average]
  (min, avg, max) = (9.780, 9.817, 9.862), stdev = 0.041
  CI (99.9%): [9.065, 10.570] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.491 ops/ms
# Warmup Iteration   2: 7.621 ops/ms
# Warmup Iteration   3: 8.244 ops/ms
Iteration   1: 8.249 ops/ms
Iteration   2: 8.200 ops/ms
Iteration   3: 8.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.240 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (8.200, 8.240, 8.271), stdev = 0.036
  CI (99.9%): [7.575, 8.904] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.171 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.004 ms/op
Iteration   1: 3.262 ±(99.9%) 0.003 ms/op
Iteration   2: 3.354 ±(99.9%) 0.003 ms/op
Iteration   3: 3.355 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.324 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.262, 3.324, 3.355), stdev = 0.053
  CI (99.9%): [2.350, 4.298] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.350 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.003 ms/op
Iteration   1: 3.099 ±(99.9%) 0.006 ms/op
Iteration   2: 3.167 ±(99.9%) 0.005 ms/op
Iteration   3: 3.162 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.143 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.099, 3.143, 3.167), stdev = 0.038
  CI (99.9%): [2.452, 3.833] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.042 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.004 ms/op
Iteration   1: 3.263 ±(99.9%) 0.005 ms/op
Iteration   2: 3.216 ±(99.9%) 0.004 ms/op
Iteration   3: 3.246 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.242 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.216, 3.242, 3.263), stdev = 0.024
  CI (99.9%): [2.805, 3.679] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.857 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.003 ms/op
Iteration   1: 3.813 ±(99.9%) 0.005 ms/op
Iteration   2: 3.821 ±(99.9%) 0.004 ms/op
Iteration   3: 3.947 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.860 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.813, 3.860, 3.947), stdev = 0.075
  CI (99.9%): [2.488, 5.232] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  17.442 ms/op
                 createUser·p0.9999: 20.451 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.257 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  19.655 ms/op
                 createUser·p0.9999: 26.009 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  16.365 ms/op
                 createUser·p0.9999: 18.650 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291422
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14821 
    [ 2.500,  5.000) = 268018 
    [ 5.000,  7.500) = 7053 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     17.058 ms/op
     p(99.9900) =     24.244 ms/op
     p(99.9990) =     26.610 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.665 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  12.253 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.130 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   5.948 ms/op
                 existUser·p0.999:  9.534 ms/op
                 existUser·p0.9999: 34.262 ms/op
                 existUser·p1.00:   35.914 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 21.974 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300193
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14991 
    [ 2.500,  5.000) = 277254 
    [ 5.000,  7.500) = 6560 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =      9.893 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.804 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.012 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  10.719 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 22.825 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  11.952 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300627
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10201 
    [ 2.500,  5.000) = 283933 
    [ 5.000,  7.500) = 5281 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     11.016 ms/op
     p(99.9900) =     21.887 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.633 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.013 ms/op
Iteration   1: 3.816 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 25.141 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 16.318 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   3: 3.761 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  13.203 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254982
  mean =      3.763 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 245867 
    [ 5.000,  7.500) = 6497 
    [ 7.500, 10.000) = 1838 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     23.806 ms/op
     p(99.9990) =     26.131 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.526 ± 0.480  ops/ms
ClientPb.existUser                       thrpt       3  10.247 ± 5.652  ops/ms
ClientPb.getUser                         thrpt       3   9.817 ± 0.752  ops/ms
ClientPb.listUser                        thrpt       3   8.240 ± 0.664  ops/ms
ClientPb.createUser                       avgt       3   3.324 ± 0.974   ms/op
ClientPb.existUser                        avgt       3   3.143 ± 0.691   ms/op
ClientPb.getUser                          avgt       3   3.242 ± 0.437   ms/op
ClientPb.listUser                         avgt       3   3.860 ± 1.372   ms/op
ClientPb.createUser                     sample  291422   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.950           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.058           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.244           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.984           ms/op
ClientPb.existUser                      sample  300193   3.196 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.442           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.893           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.751           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914           ms/op
ClientPb.getUser                        sample  300627   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.904           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.016           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.887           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.428           ms/op
ClientPb.listUser                       sample  254982   3.763 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.571           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.806           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.247           ms/op
