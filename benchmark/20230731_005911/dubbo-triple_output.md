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
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 5.285 ops/ms
# Warmup Iteration   3: 8.457 ops/ms
Iteration   1: 9.431 ops/ms
Iteration   2: 9.592 ops/ms
Iteration   3: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.373 ±(99.9%) 4.617 ops/ms [Average]
  (min, avg, max) = (9.096, 9.373, 9.592), stdev = 0.253
  CI (99.9%): [4.757, 13.990] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.610 ops/ms
Iteration   1: 9.669 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.576 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (9.459, 9.576, 9.669), stdev = 0.107
  CI (99.9%): [7.626, 11.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.561 ops/ms
# Warmup Iteration   2: 8.148 ops/ms
# Warmup Iteration   3: 9.134 ops/ms
Iteration   1: 9.225 ops/ms
Iteration   2: 9.301 ops/ms
Iteration   3: 8.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.172 ±(99.9%) 2.952 ops/ms [Average]
  (min, avg, max) = (8.990, 9.172, 9.301), stdev = 0.162
  CI (99.9%): [6.220, 12.124] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.610 ops/ms
# Warmup Iteration   2: 7.157 ops/ms
# Warmup Iteration   3: 7.742 ops/ms
Iteration   1: 8.028 ops/ms
Iteration   2: 8.138 ops/ms
Iteration   3: 8.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.099 ±(99.9%) 1.118 ops/ms [Average]
  (min, avg, max) = (8.028, 8.099, 8.138), stdev = 0.061
  CI (99.9%): [6.981, 9.217] (assumes normal distribution)


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
# Warmup Iteration   1: 9.735 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.007 ms/op
Iteration   1: 3.520 ±(99.9%) 0.007 ms/op
Iteration   2: 3.444 ±(99.9%) 0.010 ms/op
Iteration   3: 3.480 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.481 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.444, 3.481, 3.520), stdev = 0.038
  CI (99.9%): [2.790, 4.173] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.225 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.005 ms/op
Iteration   1: 3.342 ±(99.9%) 0.005 ms/op
Iteration   2: 3.243 ±(99.9%) 0.006 ms/op
Iteration   3: 3.284 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.289 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (3.243, 3.289, 3.342), stdev = 0.050
  CI (99.9%): [2.377, 4.202] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.592 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.002 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
Iteration   2: 3.392 ±(99.9%) 0.008 ms/op
Iteration   3: 3.479 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.432 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.392, 3.432, 3.479), stdev = 0.044
  CI (99.9%): [2.633, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 11.236 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.937 ±(99.9%) 0.015 ms/op
Iteration   2: 3.981 ±(99.9%) 0.009 ms/op
Iteration   3: 3.953 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.957 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.937, 3.957, 3.981), stdev = 0.022
  CI (99.9%): [3.553, 4.360] (assumes normal distribution)


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
# Warmup Iteration   1: 10.720 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.012 ms/op
Iteration   1: 3.510 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 24.303 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.563 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  23.593 ms/op
                 createUser·p0.9999: 30.049 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  23.076 ms/op
                 createUser·p0.9999: 27.803 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273422
  mean =      3.507 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6663 
    [ 2.500,  5.000) = 261642 
    [ 5.000,  7.500) = 4074 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 156 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 8.949 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.009 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  20.051 ms/op
                 existUser·p0.9999: 23.324 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.280 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  11.754 ms/op
                 existUser·p0.9999: 39.927 ms/op
                 existUser·p1.00:   41.026 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 27.244 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291461
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 287265 
    [ 5.000, 10.000) = 3758 
    [10.000, 15.000) = 182 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 98 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     38.450 ms/op
     p(99.9990) =     40.376 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


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
# Warmup Iteration   1: 10.555 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.010 ms/op
Iteration   1: 3.568 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.702 ms/op
                 getUser·p0.999:  18.032 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   2: 3.427 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  18.514 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.776 ms/op
                 getUser·p0.9999: 41.681 ms/op
                 getUser·p1.00:   42.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273350
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 263865 
    [ 5.000, 10.000) = 8963 
    [10.000, 15.000) = 201 
    [15.000, 20.000) = 191 
    [20.000, 25.000) = 98 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.042 ms/op
     p(99.9000) =     18.240 ms/op
     p(99.9900) =     38.644 ms/op
     p(99.9990) =     42.572 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


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
# Warmup Iteration   1: 10.204 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.015 ms/op
Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  21.922 ms/op
                 listUser·p0.9999: 25.710 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.960 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.968 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.670 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  16.500 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237695
  mean =      4.036 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 228436 
    [ 5.000,  7.500) = 6906 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     17.180 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.452 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.373 ± 4.617  ops/ms
ClientPb.existUser                       thrpt       3   9.576 ± 1.950  ops/ms
ClientPb.getUser                         thrpt       3   9.172 ± 2.952  ops/ms
ClientPb.listUser                        thrpt       3   8.099 ± 1.118  ops/ms
ClientPb.createUser                       avgt       3   3.481 ± 0.691   ms/op
ClientPb.existUser                        avgt       3   3.289 ± 0.912   ms/op
ClientPb.getUser                          avgt       3   3.432 ± 0.799   ms/op
ClientPb.listUser                         avgt       3   3.957 ± 0.404   ms/op
ClientPb.createUser                     sample  273422   3.507 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.079           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.046           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.279           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.867           ms/op
ClientPb.existUser                      sample  291461   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.348           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.764           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.450           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.026           ms/op
ClientPb.getUser                        sample  273350   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.339           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.042           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.240           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.644           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.926           ms/op
ClientPb.listUser                       sample  237695   4.036 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.670           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.180           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
