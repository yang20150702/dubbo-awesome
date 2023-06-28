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
# Warmup Iteration   1: 2.841 ops/ms
# Warmup Iteration   2: 6.779 ops/ms
# Warmup Iteration   3: 9.509 ops/ms
Iteration   1: 9.731 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 10.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.851 ±(99.9%) 3.491 ops/ms [Average]
  (min, avg, max) = (9.731, 9.851, 10.072), stdev = 0.191
  CI (99.9%): [6.360, 13.343] (assumes normal distribution)


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
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 9.097 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.436 ops/ms
Iteration   2: 10.154 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.431 ±(99.9%) 4.991 ops/ms [Average]
  (min, avg, max) = (10.154, 10.431, 10.701), stdev = 0.274
  CI (99.9%): [5.439, 15.422] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 10.042 ops/ms
Iteration   1: 9.905 ops/ms
Iteration   2: 9.704 ops/ms
Iteration   3: 10.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.918 ±(99.9%) 4.016 ops/ms [Average]
  (min, avg, max) = (9.704, 9.918, 10.144), stdev = 0.220
  CI (99.9%): [5.901, 13.934] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ops/ms
# Warmup Iteration   2: 8.025 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.276 ops/ms
Iteration   2: 8.553 ops/ms
Iteration   3: 8.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.534 ±(99.9%) 4.543 ops/ms [Average]
  (min, avg, max) = (8.276, 8.534, 8.773), stdev = 0.249
  CI (99.9%): [3.990, 13.077] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.003 ms/op
Iteration   1: 3.191 ±(99.9%) 0.011 ms/op
Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
Iteration   3: 3.106 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.173 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.106, 3.173, 3.221), stdev = 0.060
  CI (99.9%): [2.087, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 8.031 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.007 ms/op
Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
Iteration   3: 3.159 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.127 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.056, 3.127, 3.168), stdev = 0.062
  CI (99.9%): [1.999, 4.256] (assumes normal distribution)


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
# Warmup Iteration   1: 8.394 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.006 ms/op
Iteration   1: 3.167 ±(99.9%) 0.004 ms/op
Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
Iteration   3: 3.357 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.265 ±(99.9%) 1.738 ms/op [Average]
  (min, avg, max) = (3.167, 3.265, 3.357), stdev = 0.095
  CI (99.9%): [1.527, 5.003] (assumes normal distribution)


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
# Warmup Iteration   1: 8.959 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.009 ms/op
Iteration   1: 3.625 ±(99.9%) 0.006 ms/op
Iteration   2: 3.760 ±(99.9%) 0.005 ms/op
Iteration   3: 3.804 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.730 ±(99.9%) 1.698 ms/op [Average]
  (min, avg, max) = (3.625, 3.730, 3.804), stdev = 0.093
  CI (99.9%): [2.032, 5.428] (assumes normal distribution)


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
# Warmup Iteration   1: 8.425 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.105 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 23.190 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.742 ms/op
                 createUser·p0.99:   5.190 ms/op
                 createUser·p0.999:  19.436 ms/op
                 createUser·p0.9999: 22.683 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  13.530 ms/op
                 createUser·p0.9999: 17.299 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306863
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19888 
    [ 2.500,  5.000) = 282825 
    [ 5.000,  7.500) = 3358 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     15.223 ms/op
     p(99.9900) =     22.719 ms/op
     p(99.9990) =     23.985 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 7.574 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.328 ms/op
                 existUser·p0.9999: 19.259 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  18.055 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   4.519 ms/op
                 existUser·p0.999:  11.028 ms/op
                 existUser·p0.9999: 15.422 ms/op
                 existUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313734
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18320 
    [ 2.500,  5.000) = 291542 
    [ 5.000,  7.500) = 3100 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.114 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 7.432 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.225 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  15.909 ms/op
                 getUser·p0.9999: 20.040 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.302 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  12.159 ms/op
                 getUser·p0.9999: 25.209 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 26.120 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295428
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17281 
    [ 2.500,  5.000) = 270635 
    [ 5.000,  7.500) = 6556 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     25.115 ms/op
     p(99.9990) =     26.755 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 8.653 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.011 ms/op
Iteration   1: 3.735 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.931 ms/op
                 listUser·p0.999:  17.996 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.736 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 16.056 ms/op
                 listUser·p1.00:   16.073 ms/op

Iteration   3: 3.768 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.368 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  12.880 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256398
  mean =      3.746 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 248620 
    [ 5.000,  7.500) = 5345 
    [ 7.500, 10.000) = 1605 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     19.804 ms/op
     p(99.9990) =     20.560 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.851 ± 3.491  ops/ms
ClientPb.existUser                       thrpt       3  10.431 ± 4.991  ops/ms
ClientPb.getUser                         thrpt       3   9.918 ± 4.016  ops/ms
ClientPb.listUser                        thrpt       3   8.534 ± 4.543  ops/ms
ClientPb.createUser                       avgt       3   3.173 ± 1.086   ms/op
ClientPb.existUser                        avgt       3   3.127 ± 1.129   ms/op
ClientPb.getUser                          avgt       3   3.265 ± 1.738   ms/op
ClientPb.listUser                         avgt       3   3.730 ± 1.698   ms/op
ClientPb.createUser                     sample  306863   3.127 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.073           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.223           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.719           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  313734   3.060 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.625           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  295428   3.248 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.104           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.565           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.115           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.230           ms/op
ClientPb.listUser                       sample  256398   3.746 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.407           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.025           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.804           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.677           ms/op
