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
# Warmup Iteration   1: 2.032 ops/ms
# Warmup Iteration   2: 5.209 ops/ms
# Warmup Iteration   3: 8.632 ops/ms
Iteration   1: 9.215 ops/ms
Iteration   2: 9.252 ops/ms
Iteration   3: 9.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.279 ±(99.9%) 1.499 ops/ms [Average]
  (min, avg, max) = (9.215, 9.279, 9.372), stdev = 0.082
  CI (99.9%): [7.780, 10.779] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.695 ops/ms
# Warmup Iteration   2: 8.245 ops/ms
# Warmup Iteration   3: 9.250 ops/ms
Iteration   1: 9.468 ops/ms
Iteration   2: 9.495 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.555 ±(99.9%) 2.353 ops/ms [Average]
  (min, avg, max) = (9.468, 9.555, 9.704), stdev = 0.129
  CI (99.9%): [7.203, 11.908] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.092 ops/ms
# Warmup Iteration   2: 8.234 ops/ms
# Warmup Iteration   3: 9.005 ops/ms
Iteration   1: 9.083 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.188 ±(99.9%) 2.102 ops/ms [Average]
  (min, avg, max) = (9.083, 9.188, 9.311), stdev = 0.115
  CI (99.9%): [7.086, 11.290] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.803 ops/ms
# Warmup Iteration   2: 7.081 ops/ms
# Warmup Iteration   3: 7.550 ops/ms
Iteration   1: 7.739 ops/ms
Iteration   2: 7.842 ops/ms
Iteration   3: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.882 ±(99.9%) 3.029 ops/ms [Average]
  (min, avg, max) = (7.739, 7.882, 8.064), stdev = 0.166
  CI (99.9%): [4.853, 10.911] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.956 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.009 ms/op
Iteration   1: 3.580 ±(99.9%) 0.005 ms/op
Iteration   2: 3.417 ±(99.9%) 0.007 ms/op
Iteration   3: 3.369 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.456 ±(99.9%) 2.020 ms/op [Average]
  (min, avg, max) = (3.369, 3.456, 3.580), stdev = 0.111
  CI (99.9%): [1.436, 5.476] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.936 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.005 ms/op
Iteration   1: 3.366 ±(99.9%) 0.004 ms/op
Iteration   2: 3.371 ±(99.9%) 0.005 ms/op
Iteration   3: 3.276 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (3.276, 3.338, 3.371), stdev = 0.053
  CI (99.9%): [2.365, 4.311] (assumes normal distribution)


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
# Warmup Iteration   1: 10.018 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.005 ms/op
Iteration   1: 3.503 ±(99.9%) 0.003 ms/op
Iteration   2: 3.437 ±(99.9%) 0.008 ms/op
Iteration   3: 3.461 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.437, 3.467, 3.503), stdev = 0.033
  CI (99.9%): [2.857, 4.077] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.429 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.006 ms/op
Iteration   1: 4.064 ±(99.9%) 0.007 ms/op
Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
Iteration   3: 4.009 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.024 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (4.000, 4.024, 4.064), stdev = 0.035
  CI (99.9%): [3.393, 4.655] (assumes normal distribution)


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
# Warmup Iteration   1: 9.491 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.011 ms/op
Iteration   1: 3.696 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.362 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.659 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.755 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.546 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 21.997 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   3: 3.573 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  13.355 ms/op
                 createUser·p0.9999: 25.567 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263508
  mean =      3.642 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3980 
    [ 2.500,  5.000) = 249619 
    [ 5.000,  7.500) = 8146 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     22.940 ms/op
     p(99.9990) =     26.462 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 8.101 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.010 ms/op
Iteration   1: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   6.244 ms/op
                 existUser·p0.999:  20.970 ms/op
                 existUser·p0.9999: 23.959 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.328 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   6.182 ms/op
                 existUser·p0.999:  20.916 ms/op
                 existUser·p0.9999: 28.750 ms/op
                 existUser·p1.00:   30.933 ms/op

Iteration   3: 3.384 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  24.564 ms/op
                 existUser·p0.9999: 30.755 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286252
  mean =      3.352 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3148 
    [ 2.500,  5.000) = 275140 
    [ 5.000,  7.500) = 6626 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     21.086 ms/op
     p(99.9900) =     29.667 ms/op
     p(99.9990) =     31.134 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 9.487 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.012 ms/op
Iteration   1: 3.579 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.567 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 26.412 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 3.555 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  22.774 ms/op
                 getUser·p0.9999: 28.541 ms/op
                 getUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268929
  mean =      3.567 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5725 
    [ 2.500,  5.000) = 254226 
    [ 5.000,  7.500) = 7271 
    [ 7.500, 10.000) = 1072 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     20.155 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     29.573 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 12.348 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.015 ms/op
Iteration   1: 4.177 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  20.722 ms/op
                 listUser·p0.9999: 24.008 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   2: 4.120 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  16.157 ms/op
                 listUser·p0.9999: 23.044 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 4.178 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  16.432 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230727
  mean =      4.158 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 218698 
    [ 5.000,  7.500) = 8331 
    [ 7.500, 10.000) = 2457 
    [10.000, 12.500) = 584 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.490 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.279 ± 1.499  ops/ms
ClientPb.existUser                       thrpt       3   9.555 ± 2.353  ops/ms
ClientPb.getUser                         thrpt       3   9.188 ± 2.102  ops/ms
ClientPb.listUser                        thrpt       3   7.882 ± 3.029  ops/ms
ClientPb.createUser                       avgt       3   3.456 ± 2.020   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 0.973   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 0.610   ms/op
ClientPb.listUser                         avgt       3   4.024 ± 0.631   ms/op
ClientPb.createUser                     sample  263508   3.642 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.714           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.940           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  286252   3.352 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.086           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.667           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  268929   3.567 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.321           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.155           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.870           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  230727   4.158 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.380           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.101           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.969           ms/op
