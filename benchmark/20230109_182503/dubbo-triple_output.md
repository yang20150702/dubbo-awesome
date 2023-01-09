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
# Warmup Iteration   1: 2.476 ops/ms
# Warmup Iteration   2: 6.373 ops/ms
# Warmup Iteration   3: 9.482 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.167 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.094 ±(99.9%) 1.523 ops/ms [Average]
  (min, avg, max) = (10.003, 10.094, 10.167), stdev = 0.083
  CI (99.9%): [8.571, 11.617] (assumes normal distribution)


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
# Warmup Iteration   1: 3.772 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 10.367 ops/ms
Iteration   1: 10.842 ops/ms
Iteration   2: 10.417 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.482 ±(99.9%) 6.064 ops/ms [Average]
  (min, avg, max) = (10.187, 10.482, 10.842), stdev = 0.332
  CI (99.9%): [4.418, 16.546] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.139 ops/ms
# Warmup Iteration   2: 8.712 ops/ms
# Warmup Iteration   3: 9.422 ops/ms
Iteration   1: 9.737 ops/ms
Iteration   2: 10.402 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 6.211 ops/ms [Average]
  (min, avg, max) = (9.737, 10.111, 10.402), stdev = 0.340
  CI (99.9%): [3.899, 16.322] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.407 ops/ms
# Warmup Iteration   2: 7.843 ops/ms
# Warmup Iteration   3: 8.501 ops/ms
Iteration   1: 8.583 ops/ms
Iteration   2: 8.445 ops/ms
Iteration   3: 8.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.497 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (8.445, 8.497, 8.583), stdev = 0.075
  CI (99.9%): [7.126, 9.868] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.004 ms/op
Iteration   1: 3.216 ±(99.9%) 0.004 ms/op
Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
Iteration   3: 3.095 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 1.379 ms/op [Average]
  (min, avg, max) = (3.095, 3.181, 3.234), stdev = 0.076
  CI (99.9%): [1.802, 4.561] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.541 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
Iteration   3: 3.016 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.078 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (3.016, 3.078, 3.143), stdev = 0.064
  CI (99.9%): [1.918, 4.239] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.948 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.005 ms/op
Iteration   1: 3.295 ±(99.9%) 0.006 ms/op
Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
Iteration   3: 3.160 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.217 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (3.160, 3.217, 3.295), stdev = 0.070
  CI (99.9%): [1.946, 4.488] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.960 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.007 ms/op
Iteration   1: 3.710 ±(99.9%) 0.011 ms/op
Iteration   2: 3.885 ±(99.9%) 0.004 ms/op
Iteration   3: 3.784 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.793 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (3.710, 3.793, 3.885), stdev = 0.088
  CI (99.9%): [2.188, 5.398] (assumes normal distribution)


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
# Warmup Iteration   1: 8.974 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.011 ms/op
Iteration   1: 3.299 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  13.397 ms/op
                 createUser·p0.9999: 26.487 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.142 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  19.337 ms/op
                 createUser·p0.9999: 23.947 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.360 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 19.464 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293991
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15698 
    [ 2.500,  5.000) = 272869 
    [ 5.000,  7.500) = 4514 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     27.269 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.280 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.008 ms/op
Iteration   1: 3.089 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  11.231 ms/op
                 existUser·p0.9999: 20.141 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.301 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  8.374 ms/op
                 existUser·p0.9999: 22.726 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.497 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312258
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31701 
    [ 2.500,  5.000) = 276747 
    [ 5.000,  7.500) = 3124 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      5.153 ms/op
     p(99.9000) =     10.727 ms/op
     p(99.9900) =     22.275 ms/op
     p(99.9990) =     23.192 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.778 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.010 ms/op
Iteration   1: 3.191 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  11.829 ms/op
                 getUser·p0.9999: 25.001 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 3.170 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.837 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   3: 3.127 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.975 ms/op
                 getUser·p0.999:  12.021 ms/op
                 getUser·p0.9999: 32.211 ms/op
                 getUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303566
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10095 
    [ 2.500,  5.000) = 287503 
    [ 5.000,  7.500) = 5040 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     31.202 ms/op
     p(99.9990) =     32.663 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 8.957 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.012 ms/op
Iteration   1: 3.680 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   5.681 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 3.723 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 13.418 ms/op
                 listUser·p1.00:   14.123 ms/op

Iteration   3: 3.716 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 14.057 ms/op
                 listUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258986
  mean =      3.706 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 252764 
    [ 5.000,  7.500) = 4583 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     18.943 ms/op
     p(99.9990) =     20.759 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.094 ± 1.523  ops/ms
ClientPb.existUser                       thrpt       3  10.482 ± 6.064  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 6.211  ops/ms
ClientPb.listUser                        thrpt       3   8.497 ± 1.371  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 1.379   ms/op
ClientPb.existUser                        avgt       3   3.078 ± 1.160   ms/op
ClientPb.getUser                          avgt       3   3.217 ± 1.271   ms/op
ClientPb.listUser                         avgt       3   3.793 ± 1.605   ms/op
ClientPb.createUser                     sample  293991   3.264 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.081           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.041           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.707           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  312258   3.071 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.727           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.275           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  303566   3.163 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.990           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.202           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.030           ms/op
ClientPb.listUser                       sample  258986   3.706 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.927           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.943           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.135           ms/op
