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
# Warmup Iteration   1: 2.468 ops/ms
# Warmup Iteration   2: 5.915 ops/ms
# Warmup Iteration   3: 9.145 ops/ms
Iteration   1: 9.791 ops/ms
Iteration   2: 10.154 ops/ms
Iteration   3: 10.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.985 ±(99.9%) 3.336 ops/ms [Average]
  (min, avg, max) = (9.791, 9.985, 10.154), stdev = 0.183
  CI (99.9%): [6.649, 13.321] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ops/ms
# Warmup Iteration   2: 9.326 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 10.266 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.121 ±(99.9%) 2.630 ops/ms [Average]
  (min, avg, max) = (9.978, 10.121, 10.266), stdev = 0.144
  CI (99.9%): [7.491, 12.752] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ops/ms
# Warmup Iteration   2: 9.036 ops/ms
# Warmup Iteration   3: 9.683 ops/ms
Iteration   1: 9.772 ops/ms
Iteration   2: 9.842 ops/ms
Iteration   3: 9.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.773 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (9.705, 9.773, 9.842), stdev = 0.069
  CI (99.9%): [8.520, 11.026] (assumes normal distribution)


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
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.534 ops/ms
# Warmup Iteration   3: 8.099 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.236 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.398 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (8.236, 8.398, 8.529), stdev = 0.149
  CI (99.9%): [5.677, 11.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.109 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.002 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
Iteration   2: 3.254 ±(99.9%) 0.006 ms/op
Iteration   3: 3.279 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.301 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (3.254, 3.301, 3.369), stdev = 0.060
  CI (99.9%): [2.205, 4.397] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.862 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.005 ms/op
Iteration   1: 3.126 ±(99.9%) 0.004 ms/op
Iteration   2: 3.080 ±(99.9%) 0.004 ms/op
Iteration   3: 3.052 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.086 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.052, 3.086, 3.126), stdev = 0.037
  CI (99.9%): [2.409, 3.763] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.428 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.004 ms/op
Iteration   1: 3.302 ±(99.9%) 0.005 ms/op
Iteration   2: 3.230 ±(99.9%) 0.005 ms/op
Iteration   3: 3.197 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.197, 3.243, 3.302), stdev = 0.053
  CI (99.9%): [2.268, 4.218] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.090 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.004 ms/op
Iteration   1: 3.772 ±(99.9%) 0.007 ms/op
Iteration   2: 3.808 ±(99.9%) 0.005 ms/op
Iteration   3: 3.714 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.765 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (3.714, 3.765, 3.808), stdev = 0.047
  CI (99.9%): [2.906, 4.623] (assumes normal distribution)


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
# Warmup Iteration   1: 7.221 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
Iteration   1: 3.235 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.999 ms/op
                 createUser·p0.999:  13.867 ms/op
                 createUser·p0.9999: 22.811 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  18.155 ms/op
                 createUser·p0.9999: 22.014 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  13.201 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296701
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16453 
    [ 2.500,  5.000) = 272942 
    [ 5.000,  7.500) = 5676 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     16.749 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.135 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.691 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.009 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  10.251 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   2: 3.188 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  15.248 ms/op
                 existUser·p0.9999: 25.165 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.385 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 21.758 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295115
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21571 
    [ 2.500,  5.000) = 264239 
    [ 5.000,  7.500) = 8076 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     24.113 ms/op
     p(99.9990) =     25.662 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 7.620 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.011 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  16.892 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 3.242 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  14.136 ms/op
                 getUser·p0.9999: 24.031 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.289 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  15.043 ms/op
                 getUser·p0.9999: 20.826 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290440
  mean =      3.304 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13487 
    [ 2.500,  5.000) = 265245 
    [ 5.000,  7.500) = 9804 
    [ 7.500, 10.000) = 1212 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     15.174 ms/op
     p(99.9900) =     21.789 ms/op
     p(99.9990) =     25.103 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 8.360 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.012 ms/op
Iteration   1: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  14.301 ms/op
                 listUser·p0.9999: 19.208 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 3.802 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  15.173 ms/op
                 listUser·p0.9999: 17.386 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.840 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 13.872 ms/op
                 listUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251647
  mean =      3.814 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 98 
    [ 2.500,  3.750) = 176875 
    [ 3.750,  5.000) = 63616 
    [ 5.000,  6.250) = 4426 
    [ 6.250,  7.500) = 4272 
    [ 7.500,  8.750) = 962 
    [ 8.750, 10.000) = 666 
    [10.000, 11.250) = 199 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 197 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 71 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     18.339 ms/op
     p(99.9990) =     19.365 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.985 ± 3.336  ops/ms
ClientPb.existUser                       thrpt       3  10.121 ± 2.630  ops/ms
ClientPb.getUser                         thrpt       3   9.773 ± 1.253  ops/ms
ClientPb.listUser                        thrpt       3   8.398 ± 2.721  ops/ms
ClientPb.createUser                       avgt       3   3.301 ± 1.096   ms/op
ClientPb.existUser                        avgt       3   3.086 ± 0.677   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 0.975   ms/op
ClientPb.listUser                         avgt       3   3.765 ± 0.858   ms/op
ClientPb.createUser                     sample  296701   3.232 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.217           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.265           ms/op
ClientPb.existUser                      sample  295115   3.251 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.193           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.113           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  290440   3.304 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.997           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.701           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.174           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.789           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.133           ms/op
ClientPb.listUser                       sample  251647   3.814 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.741           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.681           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.339           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.694           ms/op
