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
# Warmup Iteration   1: 2.589 ops/ms
# Warmup Iteration   2: 6.224 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.664 ±(99.9%) 7.021 ops/ms [Average]
  (min, avg, max) = (9.230, 9.664, 9.965), stdev = 0.385
  CI (99.9%): [2.642, 16.685] (assumes normal distribution)


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
# Warmup Iteration   1: 3.454 ops/ms
# Warmup Iteration   2: 9.393 ops/ms
# Warmup Iteration   3: 10.228 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.506 ±(99.9%) 0.835 ops/ms [Average]
  (min, avg, max) = (10.454, 10.506, 10.539), stdev = 0.046
  CI (99.9%): [9.671, 11.341] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ops/ms
# Warmup Iteration   2: 9.073 ops/ms
# Warmup Iteration   3: 10.036 ops/ms
Iteration   1: 10.283 ops/ms
Iteration   2: 9.957 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.082 ±(99.9%) 3.205 ops/ms [Average]
  (min, avg, max) = (9.957, 10.082, 10.283), stdev = 0.176
  CI (99.9%): [6.877, 13.288] (assumes normal distribution)


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
# Warmup Iteration   1: 3.483 ops/ms
# Warmup Iteration   2: 8.094 ops/ms
# Warmup Iteration   3: 8.446 ops/ms
Iteration   1: 8.579 ops/ms
Iteration   2: 8.601 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.583 ±(99.9%) 0.308 ops/ms [Average]
  (min, avg, max) = (8.568, 8.583, 8.601), stdev = 0.017
  CI (99.9%): [8.274, 8.891] (assumes normal distribution)


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
# Warmup Iteration   1: 8.107 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.004 ms/op
Iteration   1: 3.316 ±(99.9%) 0.006 ms/op
Iteration   2: 3.324 ±(99.9%) 0.005 ms/op
Iteration   3: 3.191 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.277 ±(99.9%) 1.359 ms/op [Average]
  (min, avg, max) = (3.191, 3.277, 3.324), stdev = 0.074
  CI (99.9%): [1.918, 4.636] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.933 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.004 ms/op
Iteration   1: 3.191 ±(99.9%) 0.002 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 3.173 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.133 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (3.035, 3.133, 3.191), stdev = 0.085
  CI (99.9%): [1.582, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 7.413 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.003 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
Iteration   2: 3.285 ±(99.9%) 0.004 ms/op
Iteration   3: 3.075 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.173 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (3.075, 3.173, 3.285), stdev = 0.105
  CI (99.9%): [1.249, 5.098] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.621 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.004 ms/op
Iteration   1: 3.762 ±(99.9%) 0.006 ms/op
Iteration   2: 3.785 ±(99.9%) 0.006 ms/op
Iteration   3: 3.658 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.735 ±(99.9%) 1.238 ms/op [Average]
  (min, avg, max) = (3.658, 3.735, 3.785), stdev = 0.068
  CI (99.9%): [2.497, 4.973] (assumes normal distribution)


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
# Warmup Iteration   1: 8.892 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
Iteration   1: 3.194 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  18.088 ms/op
                 createUser·p0.9999: 22.901 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.420 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  13.428 ms/op
                 createUser·p0.9999: 20.653 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297217
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24291 
    [ 2.500,  5.000) = 266458 
    [ 5.000,  7.500) = 5725 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     21.767 ms/op
     p(99.9990) =     24.783 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 6.835 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 22.271 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 19.483 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.878 ms/op
                 existUser·p0.9999: 22.027 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312731
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26717 
    [ 2.500,  5.000) = 280998 
    [ 5.000,  7.500) = 4278 
    [ 7.500, 10.000) = 340 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     11.908 ms/op
     p(99.9900) =     21.543 ms/op
     p(99.9990) =     23.191 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 7.143 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.011 ms/op
Iteration   1: 3.216 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  9.627 ms/op
                 getUser·p0.9999: 21.497 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  20.002 ms/op
                 getUser·p0.9999: 28.615 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.848 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301289
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12231 
    [ 2.500,  5.000) = 282813 
    [ 5.000,  7.500) = 5424 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     15.398 ms/op
     p(99.9900) =     26.848 ms/op
     p(99.9990) =     29.751 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 8.927 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 21.617 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.022 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.750 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  11.912 ms/op
                 listUser·p0.9999: 13.581 ms/op
                 listUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254975
  mean =      3.766 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 247317 
    [ 5.000,  7.500) = 5833 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     13.747 ms/op
     p(99.9900) =     19.743 ms/op
     p(99.9990) =     21.937 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.664 ± 7.021  ops/ms
ClientPb.existUser                       thrpt       3  10.506 ± 0.835  ops/ms
ClientPb.getUser                         thrpt       3  10.082 ± 3.205  ops/ms
ClientPb.listUser                        thrpt       3   8.583 ± 0.308  ops/ms
ClientPb.createUser                       avgt       3   3.277 ± 1.359   ms/op
ClientPb.existUser                        avgt       3   3.133 ± 1.551   ms/op
ClientPb.getUser                          avgt       3   3.173 ± 1.925   ms/op
ClientPb.listUser                         avgt       3   3.735 ± 1.238   ms/op
ClientPb.createUser                     sample  297217   3.228 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.046           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.909           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.767           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.854           ms/op
ClientPb.existUser                      sample  312731   3.067 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.903           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.908           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.543           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.396           ms/op
ClientPb.getUser                        sample  301289   3.185 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.914           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.398           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.848           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  254975   3.766 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.108           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.747           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.743           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118           ms/op
