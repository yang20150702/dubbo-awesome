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
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 6.064 ops/ms
# Warmup Iteration   3: 9.114 ops/ms
Iteration   1: 9.670 ops/ms
Iteration   2: 10.249 ops/ms
Iteration   3: 9.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.921 ±(99.9%) 5.420 ops/ms [Average]
  (min, avg, max) = (9.670, 9.921, 10.249), stdev = 0.297
  CI (99.9%): [4.501, 15.341] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.014 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.212 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.423 ±(99.9%) 3.358 ops/ms [Average]
  (min, avg, max) = (10.212, 10.423, 10.551), stdev = 0.184
  CI (99.9%): [7.065, 13.781] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ops/ms
# Warmup Iteration   2: 9.535 ops/ms
# Warmup Iteration   3: 10.122 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.421 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.345 ±(99.9%) 2.994 ops/ms [Average]
  (min, avg, max) = (10.157, 10.345, 10.458), stdev = 0.164
  CI (99.9%): [7.352, 13.339] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 8.665 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.564 ops/ms
Iteration   3: 8.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.536 ±(99.9%) 2.493 ops/ms [Average]
  (min, avg, max) = (8.387, 8.536, 8.656), stdev = 0.137
  CI (99.9%): [6.043, 11.029] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.629 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.007 ms/op
Iteration   1: 3.211 ±(99.9%) 0.003 ms/op
Iteration   2: 3.212 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.215 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (3.211, 3.215, 3.222), stdev = 0.006
  CI (99.9%): [3.108, 3.321] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 3.193 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.054 ±(99.9%) 2.211 ms/op [Average]
  (min, avg, max) = (2.971, 3.054, 3.193), stdev = 0.121
  CI (99.9%): [0.843, 5.265] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.760 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.003 ms/op
Iteration   1: 3.218 ±(99.9%) 0.003 ms/op
Iteration   2: 3.252 ±(99.9%) 0.005 ms/op
Iteration   3: 3.073 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.181 ±(99.9%) 1.743 ms/op [Average]
  (min, avg, max) = (3.073, 3.181, 3.252), stdev = 0.096
  CI (99.9%): [1.439, 4.924] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.002 ms/op
Iteration   1: 3.704 ±(99.9%) 0.005 ms/op
Iteration   2: 3.700 ±(99.9%) 0.002 ms/op
Iteration   3: 3.701 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.701 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (3.700, 3.701, 3.704), stdev = 0.002
  CI (99.9%): [3.663, 3.740] (assumes normal distribution)


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
# Warmup Iteration   1: 7.893 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.010 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  10.820 ms/op
                 createUser·p0.9999: 21.415 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  13.256 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.527 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  15.627 ms/op
                 createUser·p0.9999: 23.023 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306630
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24353 
    [ 2.500,  5.000) = 277945 
    [ 5.000,  7.500) = 3607 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     25.832 ms/op
     p(99.9990) =     28.274 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.092 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.297 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 19.574 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  9.242 ms/op
                 existUser·p0.9999: 22.658 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  14.074 ms/op
                 existUser·p0.9999: 19.083 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 316723
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28357 
    [ 2.500,  5.000) = 283310 
    [ 5.000,  7.500) = 4279 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     21.190 ms/op
     p(99.9990) =     23.353 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.009 ms/op
Iteration   1: 3.161 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.151 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  17.039 ms/op
                 getUser·p0.9999: 20.705 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.228 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 21.326 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.269 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  11.267 ms/op
                 getUser·p0.9999: 21.274 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300628
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24065 
    [ 2.500,  5.000) = 269772 
    [ 5.000,  7.500) = 5882 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     16.587 ms/op
     p(99.9900) =     21.002 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 7.753 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.010 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 3.763 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 13.763 ms/op
                 listUser·p1.00:   14.631 ms/op

Iteration   3: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 14.877 ms/op
                 listUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256399
  mean =      3.742 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 68 
    [ 2.500,  3.750) = 198931 
    [ 3.750,  5.000) = 50564 
    [ 5.000,  6.250) = 3345 
    [ 6.250,  7.500) = 2223 
    [ 7.500,  8.750) = 439 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 144 
    [13.750, 15.000) = 129 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     18.772 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.921 ± 5.420  ops/ms
ClientPb.existUser                       thrpt       3  10.423 ± 3.358  ops/ms
ClientPb.getUser                         thrpt       3  10.345 ± 2.994  ops/ms
ClientPb.listUser                        thrpt       3   8.536 ± 2.493  ops/ms
ClientPb.createUser                       avgt       3   3.215 ± 0.106   ms/op
ClientPb.existUser                        avgt       3   3.054 ± 2.211   ms/op
ClientPb.getUser                          avgt       3   3.181 ± 1.743   ms/op
ClientPb.listUser                         avgt       3   3.701 ± 0.038   ms/op
ClientPb.createUser                     sample  306630   3.129 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.467           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.832           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  316723   3.031 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.643           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.190           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  300628   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.151           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.587           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.002           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.249           ms/op
ClientPb.listUser                       sample  256399   3.742 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.195           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.562           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.629           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.842           ms/op
