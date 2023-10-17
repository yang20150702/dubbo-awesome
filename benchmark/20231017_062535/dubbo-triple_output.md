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
# Warmup Iteration   1: 2.560 ops/ms
# Warmup Iteration   2: 6.445 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.769 ops/ms
Iteration   2: 9.991 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.841 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (9.765, 9.841, 9.991), stdev = 0.129
  CI (99.9%): [7.485, 12.198] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.928 ops/ms
# Warmup Iteration   2: 8.949 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.089 ops/ms
Iteration   2: 10.128 ops/ms
Iteration   3: 10.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.171 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (10.089, 10.171, 10.296), stdev = 0.110
  CI (99.9%): [8.162, 12.180] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ops/ms
# Warmup Iteration   2: 9.342 ops/ms
# Warmup Iteration   3: 9.664 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 9.481 ops/ms
Iteration   3: 10.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.819 ±(99.9%) 5.774 ops/ms [Average]
  (min, avg, max) = (9.481, 9.819, 10.109), stdev = 0.317
  CI (99.9%): [4.045, 15.594] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ops/ms
# Warmup Iteration   2: 7.801 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 8.464 ops/ms
Iteration   3: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.328 ±(99.9%) 3.766 ops/ms [Average]
  (min, avg, max) = (8.091, 8.328, 8.464), stdev = 0.206
  CI (99.9%): [4.562, 12.095] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.622 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.004 ms/op
Iteration   1: 3.293 ±(99.9%) 0.005 ms/op
Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
Iteration   3: 3.273 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.271 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.247, 3.271, 3.293), stdev = 0.023
  CI (99.9%): [2.843, 3.699] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.336 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.002 ms/op
Iteration   1: 3.128 ±(99.9%) 0.004 ms/op
Iteration   2: 3.154 ±(99.9%) 0.004 ms/op
Iteration   3: 3.204 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.162 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (3.128, 3.162, 3.204), stdev = 0.039
  CI (99.9%): [2.459, 3.865] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 6.543 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.002 ms/op
Iteration   1: 3.266 ±(99.9%) 0.002 ms/op
Iteration   2: 3.213 ±(99.9%) 0.002 ms/op
Iteration   3: 3.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.175, 3.218, 3.266), stdev = 0.046
  CI (99.9%): [2.379, 4.057] (assumes normal distribution)


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
# Warmup Iteration   1: 9.018 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.005 ms/op
Iteration   1: 3.819 ±(99.9%) 0.005 ms/op
Iteration   2: 3.825 ±(99.9%) 0.006 ms/op
Iteration   3: 3.721 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.788 ±(99.9%) 1.060 ms/op [Average]
  (min, avg, max) = (3.721, 3.788, 3.825), stdev = 0.058
  CI (99.9%): [2.728, 4.849] (assumes normal distribution)


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
# Warmup Iteration   1: 7.965 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
Iteration   1: 3.306 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  16.461 ms/op
                 createUser·p0.9999: 22.106 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.743 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  14.892 ms/op
                 createUser·p0.9999: 21.933 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.258 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  16.286 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291526
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11174 
    [ 2.500,  5.000) = 275188 
    [ 5.000,  7.500) = 4435 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     23.792 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 6.889 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   5.508 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 20.472 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301094
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17557 
    [ 2.500,  5.000) = 278279 
    [ 5.000,  7.500) = 4467 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     22.078 ms/op
     p(99.9990) =     23.232 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 7.459 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.008 ms/op
Iteration   1: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 22.849 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.271 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   6.231 ms/op
                 getUser·p0.999:  19.538 ms/op
                 getUser·p0.9999: 22.166 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  15.265 ms/op
                 getUser·p0.9999: 21.135 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292760
  mean =      3.278 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12440 
    [ 2.500,  5.000) = 273824 
    [ 5.000,  7.500) = 5480 
    [ 7.500, 10.000) = 365 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     16.891 ms/op
     p(99.9900) =     21.978 ms/op
     p(99.9990) =     23.340 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 9.699 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.011 ms/op
Iteration   1: 3.901 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.858 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 22.831 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 3.850 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 17.602 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 3.894 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 17.451 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247280
  mean =      3.882 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 240077 
    [ 5.000,  7.500) = 5412 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 323 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     20.760 ms/op
     p(99.9990) =     23.502 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.841 ± 2.356  ops/ms
ClientPb.existUser                       thrpt       3  10.171 ± 2.009  ops/ms
ClientPb.getUser                         thrpt       3   9.819 ± 5.774  ops/ms
ClientPb.listUser                        thrpt       3   8.328 ± 3.766  ops/ms
ClientPb.createUser                       avgt       3   3.271 ± 0.428   ms/op
ClientPb.existUser                        avgt       3   3.162 ± 0.703   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 0.839   ms/op
ClientPb.listUser                         avgt       3   3.788 ± 1.060   ms/op
ClientPb.createUser                     sample  291526   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.059           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.905           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  301094   3.189 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.078           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.462           ms/op
ClientPb.getUser                        sample  292760   3.278 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.840           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.978           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.593           ms/op
ClientPb.listUser                       sample  247280   3.882 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.237           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.760           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.724           ms/op
