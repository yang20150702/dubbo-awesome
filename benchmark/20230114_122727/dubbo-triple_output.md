# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.532 ops/ms
# Warmup Iteration   2: 6.658 ops/ms
# Warmup Iteration   3: 9.506 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 9.975 ops/ms
Iteration   3: 10.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.042 ±(99.9%) 1.195 ops/ms [Average]
  (min, avg, max) = (9.975, 10.042, 10.106), stdev = 0.066
  CI (99.9%): [8.847, 11.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 9.617 ops/ms
# Warmup Iteration   3: 10.416 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.623 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (10.552, 10.623, 10.688), stdev = 0.068
  CI (99.9%): [9.382, 11.863] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ops/ms
# Warmup Iteration   2: 9.539 ops/ms
# Warmup Iteration   3: 10.021 ops/ms
Iteration   1: 10.279 ops/ms
Iteration   2: 10.054 ops/ms
Iteration   3: 10.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.165 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (10.054, 10.165, 10.279), stdev = 0.112
  CI (99.9%): [8.117, 12.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.531 ops/ms
# Warmup Iteration   2: 7.799 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.824 ops/ms
Iteration   2: 8.480 ops/ms
Iteration   3: 8.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 3.556 ops/ms [Average]
  (min, avg, max) = (8.480, 8.599, 8.824), stdev = 0.195
  CI (99.9%): [5.044, 12.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.005 ms/op
Iteration   1: 3.139 ±(99.9%) 0.004 ms/op
Iteration   2: 3.114 ±(99.9%) 0.004 ms/op
Iteration   3: 3.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.096 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.035, 3.096, 3.139), stdev = 0.054
  CI (99.9%): [2.104, 4.088] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.487 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.004 ms/op
Iteration   3: 3.174 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.096 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.025, 3.096, 3.174), stdev = 0.075
  CI (99.9%): [1.733, 4.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.003 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
Iteration   3: 3.089 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.066 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.035, 3.066, 3.089), stdev = 0.028
  CI (99.9%): [2.563, 3.569] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.041 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.006 ms/op
Iteration   1: 3.753 ±(99.9%) 0.006 ms/op
Iteration   2: 3.645 ±(99.9%) 0.007 ms/op
Iteration   3: 3.651 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.683 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (3.645, 3.683, 3.753), stdev = 0.060
  CI (99.9%): [2.582, 4.785] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.290 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.009 ms/op
Iteration   1: 3.086 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  11.384 ms/op
                 createUser·p0.9999: 19.822 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.486 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  17.033 ms/op
                 createUser·p0.9999: 22.822 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.404 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  9.814 ms/op
                 createUser·p0.9999: 15.368 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 312085
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20717 
    [ 2.500,  5.000) = 286848 
    [ 5.000,  7.500) = 3644 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     21.587 ms/op
     p(99.9990) =     23.032 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.907 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 18.842 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.225 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 17.542 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315053
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19835 
    [ 2.500,  5.000) = 289156 
    [ 5.000,  7.500) = 5465 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     20.955 ms/op
     p(99.9990) =     23.152 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
Iteration   1: 3.167 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  18.154 ms/op
                 getUser·p0.9999: 46.065 ms/op
                 getUser·p1.00:   46.465 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 22.044 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  10.631 ms/op
                 getUser·p0.9999: 20.139 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305866
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 300299 
    [ 5.000, 10.000) = 5155 
    [10.000, 15.000) = 124 
    [15.000, 20.000) = 164 
    [20.000, 25.000) = 92 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     42.415 ms/op
     p(99.9990) =     46.265 ms/op
     p(99.9999) =     46.465 ms/op
    p(100.0000) =     46.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.394 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.010 ms/op
Iteration   1: 3.622 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.731 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  15.595 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.623 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.740 ms/op
                 listUser·p0.95:   3.916 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.743 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 262124
  mean =      3.662 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 255050 
    [ 5.000,  7.500) = 5561 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     21.500 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.042 ± 1.195  ops/ms
ClientPb.existUser                       thrpt       3  10.623 ± 1.241  ops/ms
ClientPb.getUser                         thrpt       3  10.165 ± 2.049  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 3.556  ops/ms
ClientPb.createUser                       avgt       3   3.096 ± 0.992   ms/op
ClientPb.existUser                        avgt       3   3.096 ± 1.363   ms/op
ClientPb.getUser                          avgt       3   3.066 ± 0.503   ms/op
ClientPb.listUser                         avgt       3   3.683 ± 1.102   ms/op
ClientPb.createUser                     sample  312085   3.073 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.059           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.615           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.587           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.183           ms/op
ClientPb.existUser                      sample  315053   3.044 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.208           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.955           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.724           ms/op
ClientPb.getUser                        sample  305866   3.136 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.970           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.457           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.582           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.465           ms/op
ClientPb.listUser                       sample  262124   3.662 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.992           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
