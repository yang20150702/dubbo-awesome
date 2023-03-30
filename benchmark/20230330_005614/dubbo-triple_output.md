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
# Warmup Iteration   1: 2.157 ops/ms
# Warmup Iteration   2: 5.418 ops/ms
# Warmup Iteration   3: 8.367 ops/ms
Iteration   1: 9.233 ops/ms
Iteration   2: 9.072 ops/ms
Iteration   3: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.246 ±(99.9%) 3.299 ops/ms [Average]
  (min, avg, max) = (9.072, 9.246, 9.433), stdev = 0.181
  CI (99.9%): [5.947, 12.545] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 8.905 ops/ms
# Warmup Iteration   3: 9.316 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.635 ops/ms
Iteration   3: 9.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.744 ±(99.9%) 3.274 ops/ms [Average]
  (min, avg, max) = (9.635, 9.744, 9.951), stdev = 0.179
  CI (99.9%): [6.470, 13.018] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.449 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 9.375 ops/ms
Iteration   1: 9.682 ops/ms
Iteration   2: 9.283 ops/ms
Iteration   3: 9.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.548 ±(99.9%) 4.185 ops/ms [Average]
  (min, avg, max) = (9.283, 9.548, 9.682), stdev = 0.229
  CI (99.9%): [5.363, 13.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.601 ops/ms
# Warmup Iteration   2: 6.756 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 8.217 ops/ms
Iteration   2: 8.285 ops/ms
Iteration   3: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.192 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (8.073, 8.192, 8.285), stdev = 0.108
  CI (99.9%): [6.220, 10.164] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
Iteration   2: 3.388 ±(99.9%) 0.010 ms/op
Iteration   3: 3.348 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.383 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.348, 3.383, 3.413), stdev = 0.032
  CI (99.9%): [2.793, 3.973] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.945 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
Iteration   1: 3.234 ±(99.9%) 0.008 ms/op
Iteration   2: 3.212 ±(99.9%) 0.004 ms/op
Iteration   3: 3.238 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.228 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.212, 3.228, 3.238), stdev = 0.014
  CI (99.9%): [2.970, 3.486] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.130 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.005 ms/op
Iteration   1: 3.376 ±(99.9%) 0.002 ms/op
Iteration   2: 3.487 ±(99.9%) 0.007 ms/op
Iteration   3: 3.436 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.433 ±(99.9%) 1.022 ms/op [Average]
  (min, avg, max) = (3.376, 3.433, 3.487), stdev = 0.056
  CI (99.9%): [2.411, 4.455] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.944 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.008 ms/op
Iteration   1: 4.006 ±(99.9%) 0.016 ms/op
Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
Iteration   3: 3.941 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.981 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (3.941, 3.981, 4.006), stdev = 0.035
  CI (99.9%): [3.334, 4.629] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.674 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
Iteration   1: 3.298 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  14.615 ms/op
                 createUser·p0.9999: 23.547 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.386 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  23.084 ms/op
                 createUser·p0.9999: 27.233 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  14.934 ms/op
                 createUser·p0.9999: 26.257 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288420
  mean =      3.328 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12065 
    [ 2.500,  5.000) = 271424 
    [ 5.000,  7.500) = 4136 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     17.612 ms/op
     p(99.9900) =     26.809 ms/op
     p(99.9990) =     28.936 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 8.273 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.009 ms/op
Iteration   1: 3.271 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  9.113 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.279 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.923 ms/op
                 existUser·p0.9999: 34.079 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   3: 3.223 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  12.299 ms/op
                 existUser·p0.9999: 35.324 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294759
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5769 
    [ 2.500,  5.000) = 284273 
    [ 5.000,  7.500) = 3904 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.079 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     35.917 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.783 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.011 ms/op
Iteration   1: 3.583 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.321 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.860 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  12.140 ms/op
                 getUser·p0.9999: 26.199 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  18.646 ms/op
                 getUser·p0.9999: 32.014 ms/op
                 getUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281655
  mean =      3.405 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10020 
    [ 2.500,  5.000) = 264288 
    [ 5.000,  7.500) = 6179 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     30.431 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.868 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.014 ms/op
Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.215 ms/op
                 listUser·p0.9999: 22.966 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.911 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  14.880 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   16.073 ms/op

Iteration   3: 3.912 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.644 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.425 ms/op
                 listUser·p0.9999: 16.955 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244198
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 236758 
    [ 5.000,  7.500) = 5498 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.267 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     23.236 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.246 ± 3.299  ops/ms
ClientPb.existUser                       thrpt       3   9.744 ± 3.274  ops/ms
ClientPb.getUser                         thrpt       3   9.548 ± 4.185  ops/ms
ClientPb.listUser                        thrpt       3   8.192 ± 1.972  ops/ms
ClientPb.createUser                       avgt       3   3.383 ± 0.590   ms/op
ClientPb.existUser                        avgt       3   3.228 ± 0.258   ms/op
ClientPb.getUser                          avgt       3   3.433 ± 1.022   ms/op
ClientPb.listUser                         avgt       3   3.981 ± 0.647   ms/op
ClientPb.createUser                     sample  288420   3.328 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.311           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.809           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  294759   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.257           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.079           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.275           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  281655   3.405 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.709           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.431           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.735           ms/op
ClientPb.listUser                       sample  244198   3.929 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.644           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.267           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.398           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
