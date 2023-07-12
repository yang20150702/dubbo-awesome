# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.592 ops/ms
# Warmup Iteration   2: 6.685 ops/ms
# Warmup Iteration   3: 9.484 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 10.032 ops/ms
Iteration   3: 9.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.928 ±(99.9%) 3.451 ops/ms [Average]
  (min, avg, max) = (9.710, 9.928, 10.044), stdev = 0.189
  CI (99.9%): [6.478, 13.379] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 8.380 ops/ms
# Warmup Iteration   3: 9.715 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 10.247 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.345 ±(99.9%) 5.741 ops/ms [Average]
  (min, avg, max) = (10.092, 10.345, 10.697), stdev = 0.315
  CI (99.9%): [4.604, 16.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ops/ms
# Warmup Iteration   2: 8.640 ops/ms
# Warmup Iteration   3: 9.824 ops/ms
Iteration   1: 10.142 ops/ms
Iteration   2: 10.405 ops/ms
Iteration   3: 10.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.270 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (10.142, 10.270, 10.405), stdev = 0.132
  CI (99.9%): [7.868, 12.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.151 ops/ms
# Warmup Iteration   2: 7.958 ops/ms
# Warmup Iteration   3: 8.391 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.294 ops/ms
Iteration   3: 8.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.353 ±(99.9%) 3.065 ops/ms [Average]
  (min, avg, max) = (8.222, 8.353, 8.543), stdev = 0.168
  CI (99.9%): [5.288, 11.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.885 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.004 ms/op
Iteration   1: 3.314 ±(99.9%) 0.007 ms/op
Iteration   2: 3.225 ±(99.9%) 0.011 ms/op
Iteration   3: 3.307 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.282 ±(99.9%) 0.903 ms/op [Average]
  (min, avg, max) = (3.225, 3.282, 3.314), stdev = 0.049
  CI (99.9%): [2.379, 4.185] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.471 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.004 ms/op
Iteration   1: 3.153 ±(99.9%) 0.005 ms/op
Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
Iteration   3: 3.124 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (3.013, 3.097, 3.153), stdev = 0.074
  CI (99.9%): [1.755, 4.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.514 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.004 ms/op
Iteration   1: 3.297 ±(99.9%) 0.005 ms/op
Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
Iteration   3: 3.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (3.109, 3.188, 3.297), stdev = 0.097
  CI (99.9%): [1.414, 4.963] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.140 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.004 ms/op
Iteration   1: 3.652 ±(99.9%) 0.010 ms/op
Iteration   2: 3.759 ±(99.9%) 0.007 ms/op
Iteration   3: 3.679 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.696 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.652, 3.696, 3.759), stdev = 0.056
  CI (99.9%): [2.682, 4.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.823 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.849 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  10.191 ms/op
                 createUser·p0.9999: 23.172 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.848 ms/op
                 createUser·p0.999:  10.383 ms/op
                 createUser·p0.9999: 28.767 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  14.008 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301399
  mean =      3.184 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28506 
    [ 2.500,  5.000) = 268262 
    [ 5.000,  7.500) = 3899 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     13.949 ms/op
     p(99.9900) =     27.226 ms/op
     p(99.9990) =     29.746 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.951 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  8.914 ms/op
                 existUser·p0.9999: 23.574 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.172 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 24.016 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  15.082 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306932
  mean =      3.125 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25002 
    [ 2.500,  5.000) = 276352 
    [ 5.000,  7.500) = 4642 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     14.536 ms/op
     p(99.9900) =     23.669 ms/op
     p(99.9990) =     24.373 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.387 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.010 ms/op
Iteration   1: 3.252 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  20.028 ms/op
                 getUser·p0.9999: 28.841 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  13.959 ms/op
                 getUser·p0.9999: 22.932 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  11.657 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297805
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18737 
    [ 2.500,  5.000) = 272745 
    [ 5.000,  7.500) = 5211 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     16.815 ms/op
     p(99.9900) =     28.220 ms/op
     p(99.9990) =     29.263 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.793 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.011 ms/op
Iteration   1: 3.774 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  16.382 ms/op
                 listUser·p0.9999: 19.554 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.775 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.848 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 3.673 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.893 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256599
  mean =      3.740 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 248271 
    [ 5.000,  7.500) = 5931 
    [ 7.500, 10.000) = 1518 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     14.539 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     21.922 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.928 ± 3.451  ops/ms
ClientPb.existUser                       thrpt       3  10.345 ± 5.741  ops/ms
ClientPb.getUser                         thrpt       3  10.270 ± 2.402  ops/ms
ClientPb.listUser                        thrpt       3   8.353 ± 3.065  ops/ms
ClientPb.createUser                       avgt       3   3.282 ± 0.903   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 1.342   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 1.775   ms/op
ClientPb.listUser                         avgt       3   3.696 ± 1.014   ms/op
ClientPb.createUser                     sample  301399   3.184 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.949           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.226           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  306932   3.125 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.018           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.536           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.707           ms/op
ClientPb.getUser                        sample  297805   3.222 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.815           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.220           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  256599   3.740 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.370           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.539           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.268           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.922           ms/op
