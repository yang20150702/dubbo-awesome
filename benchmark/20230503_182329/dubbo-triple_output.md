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
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 5.417 ops/ms
# Warmup Iteration   3: 9.123 ops/ms
Iteration   1: 9.840 ops/ms
Iteration   2: 10.161 ops/ms
Iteration   3: 9.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.915 ±(99.9%) 3.976 ops/ms [Average]
  (min, avg, max) = (9.744, 9.915, 10.161), stdev = 0.218
  CI (99.9%): [5.939, 13.891] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.505 ops/ms
# Warmup Iteration   2: 8.562 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.591 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (10.512, 10.591, 10.737), stdev = 0.127
  CI (99.9%): [8.273, 12.908] (assumes normal distribution)


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
# Warmup Iteration   1: 3.783 ops/ms
# Warmup Iteration   2: 9.308 ops/ms
# Warmup Iteration   3: 9.691 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.254 ops/ms
Iteration   3: 10.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.275 ±(99.9%) 2.540 ops/ms [Average]
  (min, avg, max) = (10.148, 10.275, 10.424), stdev = 0.139
  CI (99.9%): [7.736, 12.815] (assumes normal distribution)


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
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 7.829 ops/ms
# Warmup Iteration   3: 8.445 ops/ms
Iteration   1: 8.691 ops/ms
Iteration   2: 8.352 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.527 ±(99.9%) 3.100 ops/ms [Average]
  (min, avg, max) = (8.352, 8.527, 8.691), stdev = 0.170
  CI (99.9%): [5.427, 11.628] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.078 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.006 ms/op
Iteration   1: 3.227 ±(99.9%) 0.002 ms/op
Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
Iteration   3: 3.039 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.118 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.039, 3.118, 3.227), stdev = 0.097
  CI (99.9%): [1.342, 4.894] (assumes normal distribution)


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
# Warmup Iteration   1: 7.581 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.002 ms/op
Iteration   1: 3.090 ±(99.9%) 0.004 ms/op
Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.088 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.041, 3.088, 3.134), stdev = 0.047
  CI (99.9%): [2.239, 3.938] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.003 ms/op
Iteration   1: 3.300 ±(99.9%) 0.004 ms/op
Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
Iteration   3: 3.161 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.205 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (3.153, 3.205, 3.300), stdev = 0.083
  CI (99.9%): [1.697, 4.712] (assumes normal distribution)


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
# Warmup Iteration   1: 8.600 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.005 ms/op
Iteration   1: 3.800 ±(99.9%) 0.003 ms/op
Iteration   2: 3.666 ±(99.9%) 0.011 ms/op
Iteration   3: 3.656 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (3.656, 3.707, 3.800), stdev = 0.081
  CI (99.9%): [2.236, 5.178] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.021 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  17.861 ms/op
                 createUser·p0.9999: 20.031 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.664 ms/op
                 createUser·p0.9999: 22.567 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.432 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  8.582 ms/op
                 createUser·p0.9999: 18.237 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292280
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27532 
    [ 2.500,  5.000) = 256651 
    [ 5.000,  7.500) = 7297 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 195 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     20.236 ms/op
     p(99.9990) =     23.084 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 7.034 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
Iteration   1: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  12.867 ms/op
                 existUser·p0.9999: 23.109 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  12.699 ms/op
                 existUser·p0.9999: 21.782 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303734
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20078 
    [ 2.500,  5.000) = 276931 
    [ 5.000,  7.500) = 6175 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     12.334 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     26.701 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.197 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
Iteration   1: 3.295 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  12.895 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  8.452 ms/op
                 getUser·p0.9999: 27.194 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  15.215 ms/op
                 getUser·p0.9999: 22.785 ms/op
                 getUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294057
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12854 
    [ 2.500,  5.000) = 273017 
    [ 5.000,  7.500) = 7059 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     14.891 ms/op
     p(99.9900) =     26.568 ms/op
     p(99.9990) =     27.633 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.938 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.013 ms/op
Iteration   1: 3.713 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.808 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 20.493 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 20.983 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 3.654 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.315 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.632 ms/op
                 listUser·p0.9999: 18.467 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258962
  mean =      3.703 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 253538 
    [ 5.000,  7.500) = 3613 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     20.516 ms/op
     p(99.9990) =     21.324 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.915 ± 3.976  ops/ms
ClientPb.existUser                       thrpt       3  10.591 ± 2.317  ops/ms
ClientPb.getUser                         thrpt       3  10.275 ± 2.540  ops/ms
ClientPb.listUser                        thrpt       3   8.527 ± 3.100  ops/ms
ClientPb.createUser                       avgt       3   3.118 ± 1.776   ms/op
ClientPb.existUser                        avgt       3   3.088 ± 0.849   ms/op
ClientPb.getUser                          avgt       3   3.205 ± 1.507   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 1.471   ms/op
ClientPb.createUser                     sample  292280   3.283 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.811           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.396           ms/op
ClientPb.existUser                      sample  303734   3.160 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.334           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  294057   3.264 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.568           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.820           ms/op
ClientPb.listUser                       sample  258962   3.703 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.315           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.516           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118           ms/op
