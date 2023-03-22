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
# Warmup Iteration   1: 2.407 ops/ms
# Warmup Iteration   2: 6.086 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.881 ±(99.9%) 5.574 ops/ms [Average]
  (min, avg, max) = (9.626, 9.881, 10.220), stdev = 0.306
  CI (99.9%): [4.307, 15.456] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 9.137 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.291 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.284 ±(99.9%) 1.902 ops/ms [Average]
  (min, avg, max) = (10.176, 10.284, 10.385), stdev = 0.104
  CI (99.9%): [8.382, 12.186] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ops/ms
# Warmup Iteration   2: 9.006 ops/ms
# Warmup Iteration   3: 9.898 ops/ms
Iteration   1: 9.582 ops/ms
Iteration   2: 9.880 ops/ms
Iteration   3: 9.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.717 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (9.582, 9.717, 9.880), stdev = 0.151
  CI (99.9%): [6.967, 12.467] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.459 ops/ms
Iteration   1: 8.548 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.578 ±(99.9%) 1.398 ops/ms [Average]
  (min, avg, max) = (8.520, 8.578, 8.665), stdev = 0.077
  CI (99.9%): [7.180, 9.975] (assumes normal distribution)


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
# Warmup Iteration   1: 8.384 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op
Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
Iteration   3: 3.230 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.190 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.156, 3.190, 3.230), stdev = 0.037
  CI (99.9%): [2.508, 3.872] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.777 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.004 ms/op
Iteration   2: 3.103 ±(99.9%) 0.004 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.044 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (2.974, 3.044, 3.103), stdev = 0.065
  CI (99.9%): [1.854, 4.233] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.928 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.005 ms/op
Iteration   1: 3.152 ±(99.9%) 0.009 ms/op
Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
Iteration   3: 3.167 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.173 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (3.152, 3.173, 3.199), stdev = 0.024
  CI (99.9%): [2.733, 3.613] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.218 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.003 ms/op
Iteration   1: 3.812 ±(99.9%) 0.007 ms/op
Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
Iteration   3: 3.643 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.754 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (3.643, 3.754, 3.812), stdev = 0.096
  CI (99.9%): [2.001, 5.507] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.287 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
Iteration   1: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  17.557 ms/op
                 createUser·p0.9999: 22.501 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  9.215 ms/op
                 createUser·p0.9999: 20.699 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 3.075 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  14.693 ms/op
                 createUser·p0.9999: 27.924 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305151
  mean =      3.146 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15515 
    [ 2.500,  5.000) = 285318 
    [ 5.000,  7.500) = 3435 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 190 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     16.733 ms/op
     p(99.9900) =     26.198 ms/op
     p(99.9990) =     28.565 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 6.479 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.813 ms/op
                 existUser·p0.9999: 20.596 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  9.725 ms/op
                 existUser·p0.9999: 21.936 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 21.895 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313276
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24649 
    [ 2.500,  5.000) = 284225 
    [ 5.000,  7.500) = 3778 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     22.737 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 7.586 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.009 ms/op
Iteration   1: 3.181 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   4.189 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  9.070 ms/op
                 getUser·p0.9999: 22.945 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.698 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 21.261 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301180
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19675 
    [ 2.500,  5.000) = 275414 
    [ 5.000,  7.500) = 5355 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     15.353 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.971 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.012 ms/op
Iteration   1: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  16.100 ms/op
                 listUser·p0.9999: 20.959 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.719 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 21.666 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.042 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255670
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 248796 
    [ 5.000,  7.500) = 5156 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.613 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     26.684 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.881 ± 5.574  ops/ms
ClientPb.existUser                       thrpt       3  10.284 ± 1.902  ops/ms
ClientPb.getUser                         thrpt       3   9.717 ± 2.750  ops/ms
ClientPb.listUser                        thrpt       3   8.578 ± 1.398  ops/ms
ClientPb.createUser                       avgt       3   3.190 ± 0.682   ms/op
ClientPb.existUser                        avgt       3   3.044 ± 1.190   ms/op
ClientPb.getUser                          avgt       3   3.173 ± 0.440   ms/op
ClientPb.listUser                         avgt       3   3.754 ± 1.753   ms/op
ClientPb.createUser                     sample  305151   3.146 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.090           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.733           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.198           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  313276   3.062 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.594           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.003           ms/op
ClientPb.getUser                        sample  301180   3.185 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.444           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.353           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.069           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  255670   3.752 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.613           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.893           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
