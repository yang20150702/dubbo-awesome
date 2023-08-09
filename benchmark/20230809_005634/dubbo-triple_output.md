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
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 6.158 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 9.697 ops/ms
Iteration   2: 9.744 ops/ms
Iteration   3: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.625 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (9.433, 9.625, 9.744), stdev = 0.168
  CI (99.9%): [6.566, 12.683] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 9.373 ops/ms
# Warmup Iteration   3: 9.546 ops/ms
Iteration   1: 10.082 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.247 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (10.082, 10.247, 10.353), stdev = 0.144
  CI (99.9%): [7.615, 12.879] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 8.859 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 9.446 ops/ms
Iteration   2: 9.746 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.815 ±(99.9%) 7.427 ops/ms [Average]
  (min, avg, max) = (9.446, 9.815, 10.252), stdev = 0.407
  CI (99.9%): [2.388, 17.241] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.007 ops/ms
# Warmup Iteration   2: 7.477 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.384 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.397 ±(99.9%) 0.582 ops/ms [Average]
  (min, avg, max) = (8.374, 8.397, 8.433), stdev = 0.032
  CI (99.9%): [7.814, 8.979] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.355 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.003 ms/op
Iteration   1: 3.237 ±(99.9%) 0.002 ms/op
Iteration   2: 3.358 ±(99.9%) 0.005 ms/op
Iteration   3: 3.158 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.251 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (3.158, 3.251, 3.358), stdev = 0.101
  CI (99.9%): [1.414, 5.088] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.785 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.002 ms/op
Iteration   2: 3.253 ±(99.9%) 0.004 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (3.046, 3.149, 3.253), stdev = 0.103
  CI (99.9%): [1.266, 5.033] (assumes normal distribution)


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
# Warmup Iteration   1: 8.051 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.003 ms/op
Iteration   1: 3.264 ±(99.9%) 0.004 ms/op
Iteration   2: 3.199 ±(99.9%) 0.005 ms/op
Iteration   3: 3.279 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.247 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.199, 3.247, 3.279), stdev = 0.043
  CI (99.9%): [2.471, 4.023] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.788 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.007 ms/op
Iteration   1: 3.876 ±(99.9%) 0.007 ms/op
Iteration   2: 3.836 ±(99.9%) 0.006 ms/op
Iteration   3: 3.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.855 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.836, 3.855, 3.876), stdev = 0.020
  CI (99.9%): [3.482, 4.227] (assumes normal distribution)


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
# Warmup Iteration   1: 8.473 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  16.011 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  14.242 ms/op
                 createUser·p0.9999: 24.003 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.230 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  16.368 ms/op
                 createUser·p0.9999: 28.518 ms/op
                 createUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293094
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17847 
    [ 2.500,  5.000) = 267968 
    [ 5.000,  7.500) = 5831 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     26.766 ms/op
     p(99.9990) =     29.531 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.586 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.979 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 19.883 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  12.361 ms/op
                 existUser·p0.9999: 23.196 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 21.999 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299939
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17997 
    [ 2.500,  5.000) = 275610 
    [ 5.000,  7.500) = 4879 
    [ 7.500, 10.000) = 998 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 8.318 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.010 ms/op
Iteration   1: 3.373 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 34.047 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   5.541 ms/op
                 getUser·p0.999:  11.964 ms/op
                 getUser·p0.9999: 25.651 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  14.089 ms/op
                 getUser·p0.9999: 22.564 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290777
  mean =      3.300 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13210 
    [ 2.500,  5.000) = 269191 
    [ 5.000,  7.500) = 7032 
    [ 7.500, 10.000) = 885 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     14.724 ms/op
     p(99.9900) =     33.378 ms/op
     p(99.9990) =     34.731 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 8.667 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.013 ms/op
Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  15.228 ms/op
                 listUser·p0.9999: 28.720 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 3.804 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249210
  mean =      3.848 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 240207 
    [ 5.000,  7.500) = 6390 
    [ 7.500, 10.000) = 1899 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     29.167 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.625 ± 3.058  ops/ms
ClientPb.existUser                       thrpt       3  10.247 ± 2.632  ops/ms
ClientPb.getUser                         thrpt       3   9.815 ± 7.427  ops/ms
ClientPb.listUser                        thrpt       3   8.397 ± 0.582  ops/ms
ClientPb.createUser                       avgt       3   3.251 ± 1.837   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 1.883   ms/op
ClientPb.getUser                          avgt       3   3.247 ± 0.776   ms/op
ClientPb.listUser                         avgt       3   3.855 ± 0.372   ms/op
ClientPb.createUser                     sample  293094   3.272 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.177           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.318           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.766           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.622           ms/op
ClientPb.existUser                      sample  299939   3.198 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.883           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.320           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.117           ms/op
ClientPb.getUser                        sample  290777   3.300 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  249210   3.848 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.249           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.304           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.115           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
