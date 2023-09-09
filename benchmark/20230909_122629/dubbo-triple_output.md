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
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 5.154 ops/ms
# Warmup Iteration   3: 8.234 ops/ms
Iteration   1: 8.461 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.753 ±(99.9%) 7.111 ops/ms [Average]
  (min, avg, max) = (8.461, 8.753, 9.196), stdev = 0.390
  CI (99.9%): [1.642, 15.864] (assumes normal distribution)


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
# Warmup Iteration   1: 2.170 ops/ms
# Warmup Iteration   2: 7.236 ops/ms
# Warmup Iteration   3: 9.069 ops/ms
Iteration   1: 9.311 ops/ms
Iteration   2: 9.792 ops/ms
Iteration   3: 9.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.685 ±(99.9%) 6.088 ops/ms [Average]
  (min, avg, max) = (9.311, 9.685, 9.952), stdev = 0.334
  CI (99.9%): [3.598, 15.773] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 8.415 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.118 ops/ms
Iteration   2: 7.878 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.347 ±(99.9%) 12.278 ops/ms [Average]
  (min, avg, max) = (7.878, 8.347, 9.118), stdev = 0.673
  CI (99.9%): [≈ 0, 20.625] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
# Warmup Iteration   2: 6.100 ops/ms
# Warmup Iteration   3: 7.450 ops/ms
Iteration   1: 6.995 ops/ms
Iteration   2: 6.908 ops/ms
Iteration   3: 7.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.984 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (6.908, 6.984, 7.051), stdev = 0.072
  CI (99.9%): [5.663, 8.306] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.563 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.009 ms/op
Iteration   1: 3.936 ±(99.9%) 0.009 ms/op
Iteration   2: 3.944 ±(99.9%) 0.010 ms/op
Iteration   3: 3.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.807 ±(99.9%) 4.201 ms/op [Average]
  (min, avg, max) = (3.541, 3.807, 3.944), stdev = 0.230
  CI (99.9%): [≈ 0, 8.008] (assumes normal distribution)


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
# Warmup Iteration   1: 11.849 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.007 ms/op
Iteration   1: 3.758 ±(99.9%) 0.009 ms/op
Iteration   2: 3.479 ±(99.9%) 0.004 ms/op
Iteration   3: 3.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.560 ±(99.9%) 3.147 ms/op [Average]
  (min, avg, max) = (3.442, 3.560, 3.758), stdev = 0.172
  CI (99.9%): [0.413, 6.706] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.311 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.005 ms/op
Iteration   1: 3.789 ±(99.9%) 0.007 ms/op
Iteration   2: 3.693 ±(99.9%) 0.011 ms/op
Iteration   3: 3.688 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.723 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.688, 3.723, 3.789), stdev = 0.057
  CI (99.9%): [2.684, 4.762] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.876 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.008 ms/op
Iteration   1: 4.677 ±(99.9%) 0.009 ms/op
Iteration   2: 4.533 ±(99.9%) 0.010 ms/op
Iteration   3: 4.567 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.593 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (4.533, 4.593, 4.677), stdev = 0.075
  CI (99.9%): [3.218, 5.967] (assumes normal distribution)


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
# Warmup Iteration   1: 12.303 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.019 ms/op
Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  11.632 ms/op
                 createUser·p0.9999: 25.940 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.946 ms/op
                 createUser·p0.999:  22.639 ms/op
                 createUser·p0.9999: 29.291 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   3: 3.731 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   7.488 ms/op
                 createUser·p0.999:  30.633 ms/op
                 createUser·p0.9999: 48.075 ms/op
                 createUser·p1.00:   49.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 258729
  mean =      3.708 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 248781 
    [ 5.000, 10.000) = 9107 
    [10.000, 15.000) = 535 
    [15.000, 20.000) = 18 
    [20.000, 25.000) = 94 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 58 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     23.536 ms/op
     p(99.9900) =     36.397 ms/op
     p(99.9990) =     49.364 ms/op
     p(99.9999) =     49.873 ms/op
    p(100.0000) =     49.873 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 12.888 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.011 ms/op
Iteration   1: 3.635 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  23.307 ms/op
                 existUser·p0.9999: 27.808 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  21.635 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.572 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  13.398 ms/op
                 existUser·p0.9999: 29.394 ms/op
                 existUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271333
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10044 
    [ 2.500,  5.000) = 250503 
    [ 5.000,  7.500) = 9211 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     28.897 ms/op
     p(99.9990) =     29.768 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 12.329 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.023 ±(99.9%) 0.016 ms/op
Iteration   1: 3.968 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.894 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  11.616 ms/op
                 getUser·p0.9999: 23.785 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 3.549 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  21.095 ms/op
                 getUser·p0.9999: 24.376 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 4.001 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  26.270 ms/op
                 getUser·p0.9999: 30.933 ms/op
                 getUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 250822
  mean =      3.828 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2067 
    [ 2.500,  5.000) = 233888 
    [ 5.000,  7.500) = 11922 
    [ 7.500, 10.000) = 2293 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     29.390 ms/op
     p(99.9990) =     31.307 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 13.459 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.567 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.726 ±(99.9%) 0.018 ms/op
Iteration   1: 4.824 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  26.956 ms/op
                 listUser·p0.9999: 29.837 ms/op
                 listUser·p1.00:   31.588 ms/op

Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 21.767 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.744 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  16.699 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211014
  mean =      4.550 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 186168 
    [ 5.000,  7.500) = 19099 
    [ 7.500, 10.000) = 4220 
    [10.000, 12.500) = 880 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.753 ±  7.111  ops/ms
ClientPb.existUser                       thrpt       3   9.685 ±  6.088  ops/ms
ClientPb.getUser                         thrpt       3   8.347 ± 12.278  ops/ms
ClientPb.listUser                        thrpt       3   6.984 ±  1.321  ops/ms
ClientPb.createUser                       avgt       3   3.807 ±  4.201   ms/op
ClientPb.existUser                        avgt       3   3.560 ±  3.147   ms/op
ClientPb.getUser                          avgt       3   3.723 ±  1.039   ms/op
ClientPb.listUser                         avgt       3   4.593 ±  1.374   ms/op
ClientPb.createUser                     sample  258729   3.708 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.584            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.325            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.324            ms/op
ClientPb.createUser:createUser·p0.999   sample          23.536            ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.397            ms/op
ClientPb.createUser:createUser·p1.00    sample          49.873            ms/op
ClientPb.existUser                      sample  271333   3.535 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.446            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.453            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.768            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.701            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.499            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.897            ms/op
ClientPb.existUser:existUser·p1.00      sample          30.376            ms/op
ClientPb.getUser                        sample  250822   3.828 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.102            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.699            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.473            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.284            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.782            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.874            ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.390            ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556            ms/op
ClientPb.listUser                       sample  211014   4.550 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.710            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.191            ms/op
ClientPb.listUser:listUser·p0.999       sample          19.628            ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.508            ms/op
ClientPb.listUser:listUser·p1.00        sample          31.588            ms/op
