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
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 6.371 ops/ms
# Warmup Iteration   3: 9.299 ops/ms
Iteration   1: 9.808 ops/ms
Iteration   2: 9.951 ops/ms
Iteration   3: 10.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.944 ±(99.9%) 2.410 ops/ms [Average]
  (min, avg, max) = (9.808, 9.944, 10.072), stdev = 0.132
  CI (99.9%): [7.534, 12.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 9.267 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.340 ops/ms
Iteration   3: 10.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.353 ±(99.9%) 5.458 ops/ms [Average]
  (min, avg, max) = (10.061, 10.353, 10.659), stdev = 0.299
  CI (99.9%): [4.896, 15.811] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ops/ms
# Warmup Iteration   2: 9.333 ops/ms
# Warmup Iteration   3: 9.669 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 9.470 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.862 ±(99.9%) 6.383 ops/ms [Average]
  (min, avg, max) = (9.470, 9.862, 10.143), stdev = 0.350
  CI (99.9%): [3.479, 16.245] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.174 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.399 ops/ms
Iteration   3: 8.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.506 ±(99.9%) 2.149 ops/ms [Average]
  (min, avg, max) = (8.399, 8.506, 8.632), stdev = 0.118
  CI (99.9%): [6.356, 10.655] (assumes normal distribution)


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
# Warmup Iteration   1: 7.703 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.007 ms/op
Iteration   1: 3.165 ±(99.9%) 0.003 ms/op
Iteration   2: 3.252 ±(99.9%) 0.010 ms/op
Iteration   3: 3.306 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.241 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.165, 3.241, 3.306), stdev = 0.071
  CI (99.9%): [1.945, 4.537] (assumes normal distribution)


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
# Warmup Iteration   1: 7.089 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.213 ±(99.9%) 0.004 ms/op
Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
Iteration   3: 3.271 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.204 ±(99.9%) 1.320 ms/op [Average]
  (min, avg, max) = (3.127, 3.204, 3.271), stdev = 0.072
  CI (99.9%): [1.883, 4.524] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.279 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.006 ms/op
Iteration   1: 3.210 ±(99.9%) 0.003 ms/op
Iteration   2: 3.296 ±(99.9%) 0.003 ms/op
Iteration   3: 3.140 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.140, 3.215, 3.296), stdev = 0.078
  CI (99.9%): [1.791, 4.640] (assumes normal distribution)


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
# Warmup Iteration   1: 9.017 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.006 ms/op
Iteration   1: 3.744 ±(99.9%) 0.009 ms/op
Iteration   2: 3.721 ±(99.9%) 0.008 ms/op
Iteration   3: 3.966 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.811 ±(99.9%) 2.470 ms/op [Average]
  (min, avg, max) = (3.721, 3.811, 3.966), stdev = 0.135
  CI (99.9%): [1.341, 6.280] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.802 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.981 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.787 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  9.839 ms/op
                 createUser·p0.9999: 19.488 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.553 ms/op
                 createUser·p0.999:  14.303 ms/op
                 createUser·p0.9999: 25.206 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.086 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  16.722 ms/op
                 createUser·p0.9999: 25.252 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304153
  mean =      3.154 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20773 
    [ 2.500,  5.000) = 276564 
    [ 5.000,  7.500) = 6040 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.688 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.209 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.725 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.009 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 19.816 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 21.759 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  12.667 ms/op
                 existUser·p0.9999: 21.715 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315413
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16375 
    [ 2.500,  5.000) = 295143 
    [ 5.000,  7.500) = 3314 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =     11.413 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.197 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 8.366 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.010 ms/op
Iteration   1: 3.360 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  13.386 ms/op
                 getUser·p0.9999: 19.054 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  18.743 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.547 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  9.518 ms/op
                 getUser·p0.9999: 18.842 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299569
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10906 
    [ 2.500,  5.000) = 279122 
    [ 5.000,  7.500) = 8547 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     21.006 ms/op
     p(99.9990) =     22.545 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 9.271 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.011 ms/op
Iteration   1: 3.624 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.035 ms/op
                 listUser·p0.99:   6.250 ms/op
                 listUser·p0.999:  14.932 ms/op
                 listUser·p0.9999: 22.055 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.038 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.396 ms/op
                 listUser·p0.99:   7.149 ms/op
                 listUser·p0.999:  13.388 ms/op
                 listUser·p0.9999: 15.497 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.611 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.080 ms/op
                 listUser·p0.99:   5.581 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 19.665 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 262642
  mean =      3.651 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 256995 
    [ 5.000,  7.500) = 3933 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.460 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     20.952 ms/op
     p(99.9990) =     25.211 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.944 ± 2.410  ops/ms
ClientPb.existUser                       thrpt       3  10.353 ± 5.458  ops/ms
ClientPb.getUser                         thrpt       3   9.862 ± 6.383  ops/ms
ClientPb.listUser                        thrpt       3   8.506 ± 2.149  ops/ms
ClientPb.createUser                       avgt       3   3.241 ± 1.296   ms/op
ClientPb.existUser                        avgt       3   3.204 ± 1.320   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 1.425   ms/op
ClientPb.listUser                         avgt       3   3.811 ± 2.470   ms/op
ClientPb.createUser                     sample  304153   3.154 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.947           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.688           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.068           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  315413   3.042 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.722           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.413           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.724           ms/op
ClientPb.getUser                        sample  299569   3.203 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.681           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.006           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.708           ms/op
ClientPb.listUser                       sample  262642   3.651 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.341           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.572           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.460           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
