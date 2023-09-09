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
# Warmup Iteration   1: 1.685 ops/ms
# Warmup Iteration   2: 3.828 ops/ms
# Warmup Iteration   3: 7.169 ops/ms
Iteration   1: 7.340 ops/ms
Iteration   2: 8.128 ops/ms
Iteration   3: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.811 ±(99.9%) 7.594 ops/ms [Average]
  (min, avg, max) = (7.340, 7.811, 8.128), stdev = 0.416
  CI (99.9%): [0.217, 15.405] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.442 ops/ms
# Warmup Iteration   2: 7.263 ops/ms
# Warmup Iteration   3: 8.292 ops/ms
Iteration   1: 8.310 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.272 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (8.241, 8.272, 8.310), stdev = 0.035
  CI (99.9%): [7.628, 8.915] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 6.651 ops/ms
# Warmup Iteration   3: 7.643 ops/ms
Iteration   1: 7.437 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.707 ±(99.9%) 4.507 ops/ms [Average]
  (min, avg, max) = (7.437, 7.707, 7.922), stdev = 0.247
  CI (99.9%): [3.200, 12.214] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.050 ops/ms
# Warmup Iteration   2: 5.815 ops/ms
# Warmup Iteration   3: 6.343 ops/ms
Iteration   1: 6.520 ops/ms
Iteration   2: 6.617 ops/ms
Iteration   3: 6.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.603 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (6.520, 6.603, 6.670), stdev = 0.076
  CI (99.9%): [5.212, 7.993] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.062 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.043 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.396 ±(99.9%) 0.004 ms/op
Iteration   1: 4.089 ±(99.9%) 0.008 ms/op
Iteration   2: 3.924 ±(99.9%) 0.009 ms/op
Iteration   3: 4.063 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.025 ±(99.9%) 1.620 ms/op [Average]
  (min, avg, max) = (3.924, 4.025, 4.089), stdev = 0.089
  CI (99.9%): [2.405, 5.645] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.574 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.005 ms/op
Iteration   1: 3.890 ±(99.9%) 0.006 ms/op
Iteration   2: 3.835 ±(99.9%) 0.004 ms/op
Iteration   3: 3.998 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.908 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (3.835, 3.908, 3.998), stdev = 0.083
  CI (99.9%): [2.398, 5.417] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.240 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.008 ms/op
Iteration   1: 4.278 ±(99.9%) 0.004 ms/op
Iteration   2: 4.181 ±(99.9%) 0.005 ms/op
Iteration   3: 4.012 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.157 ±(99.9%) 2.453 ms/op [Average]
  (min, avg, max) = (4.012, 4.157, 4.278), stdev = 0.134
  CI (99.9%): [1.704, 6.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.965 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.631 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.013 ms/op
Iteration   1: 5.072 ±(99.9%) 0.008 ms/op
Iteration   2: 4.723 ±(99.9%) 0.017 ms/op
Iteration   3: 4.805 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.867 ±(99.9%) 3.326 ms/op [Average]
  (min, avg, max) = (4.723, 4.867, 5.072), stdev = 0.182
  CI (99.9%): [1.541, 8.193] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.278 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.997 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.020 ms/op
Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  22.102 ms/op
                 createUser·p0.9999: 24.515 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 4.097 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   6.069 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  14.527 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 4.096 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.907 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  26.528 ms/op
                 createUser·p0.9999: 28.514 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235884
  mean =      4.073 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 304 
    [ 2.500,  5.000) = 218603 
    [ 5.000,  7.500) = 13397 
    [ 7.500, 10.000) = 2553 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     28.911 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.637 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.013 ms/op
Iteration   1: 3.922 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  23.900 ms/op
                 existUser·p0.9999: 26.538 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   2: 3.962 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  13.696 ms/op
                 existUser·p0.9999: 28.302 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   3: 3.976 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  15.049 ms/op
                 existUser·p0.9999: 32.670 ms/op
                 existUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242836
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 490 
    [ 2.500,  5.000) = 228051 
    [ 5.000,  7.500) = 11361 
    [ 7.500, 10.000) = 2149 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     15.043 ms/op
     p(99.9900) =     32.309 ms/op
     p(99.9990) =     33.171 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.497 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.127 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.256 ±(99.9%) 0.016 ms/op
Iteration   1: 4.017 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  23.680 ms/op
                 getUser·p0.9999: 25.659 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   2: 4.107 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  17.241 ms/op
                 getUser·p0.9999: 31.464 ms/op
                 getUser·p1.00:   32.244 ms/op

Iteration   3: 4.014 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   5.197 ms/op
                 getUser·p0.99:   7.760 ms/op
                 getUser·p0.999:  11.982 ms/op
                 getUser·p0.9999: 33.497 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237197
  mean =      4.046 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 220596 
    [ 5.000,  7.500) = 12461 
    [ 7.500, 10.000) = 3158 
    [10.000, 12.500) = 492 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     32.197 ms/op
     p(99.9990) =     34.595 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 15.327 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.915 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.978 ±(99.9%) 0.018 ms/op
Iteration   1: 4.821 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   9.268 ms/op
                 listUser·p0.999:  24.270 ms/op
                 listUser·p0.9999: 28.551 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 4.962 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   3: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 22.098 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196926
  mean =      4.870 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 154986 
    [ 5.000,  7.500) = 35261 
    [ 7.500, 10.000) = 4555 
    [10.000, 12.500) = 1303 
    [12.500, 15.000) = 327 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     27.139 ms/op
     p(99.9990) =     29.177 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.811 ± 7.594  ops/ms
ClientPb.existUser                       thrpt       3   8.272 ± 0.643  ops/ms
ClientPb.getUser                         thrpt       3   7.707 ± 4.507  ops/ms
ClientPb.listUser                        thrpt       3   6.603 ± 1.391  ops/ms
ClientPb.createUser                       avgt       3   4.025 ± 1.620   ms/op
ClientPb.existUser                        avgt       3   3.908 ± 1.509   ms/op
ClientPb.getUser                          avgt       3   4.157 ± 2.453   ms/op
ClientPb.listUser                         avgt       3   4.867 ± 3.326   ms/op
ClientPb.createUser                     sample  235884   4.073 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.182           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.266           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.118           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.984           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  242836   3.953 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.815           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.766           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.043           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.309           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  237197   4.046 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.165           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.184           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.120           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.197           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  196926   4.870 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.095           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.158           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.135           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.139           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.590           ms/op
