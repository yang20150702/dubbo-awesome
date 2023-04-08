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
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 6.893 ops/ms
# Warmup Iteration   3: 9.413 ops/ms
Iteration   1: 9.958 ops/ms
Iteration   2: 9.891 ops/ms
Iteration   3: 10.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.988 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (9.891, 9.988, 10.115), stdev = 0.115
  CI (99.9%): [7.895, 12.081] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ops/ms
# Warmup Iteration   2: 9.413 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 10.445 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.236 ±(99.9%) 4.140 ops/ms [Average]
  (min, avg, max) = (9.994, 10.236, 10.445), stdev = 0.227
  CI (99.9%): [6.096, 14.376] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.576 ops/ms
# Warmup Iteration   2: 8.873 ops/ms
# Warmup Iteration   3: 10.200 ops/ms
Iteration   1: 9.842 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 4.976 ops/ms [Average]
  (min, avg, max) = (9.842, 10.111, 10.388), stdev = 0.273
  CI (99.9%): [5.136, 15.087] (assumes normal distribution)


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
# Warmup Iteration   1: 3.484 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.475 ops/ms
Iteration   3: 8.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.424 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (8.361, 8.424, 8.475), stdev = 0.058
  CI (99.9%): [7.369, 9.479] (assumes normal distribution)


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
# Warmup Iteration   1: 9.170 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.004 ms/op
Iteration   1: 3.216 ±(99.9%) 0.009 ms/op
Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
Iteration   3: 3.317 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.253 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.216, 3.253, 3.317), stdev = 0.056
  CI (99.9%): [2.235, 4.271] (assumes normal distribution)


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
# Warmup Iteration   1: 7.391 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
Iteration   3: 3.275 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 2.559 ms/op [Average]
  (min, avg, max) = (3.032, 3.113, 3.275), stdev = 0.140
  CI (99.9%): [0.554, 5.672] (assumes normal distribution)


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
# Warmup Iteration   1: 7.661 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.005 ms/op
Iteration   2: 3.566 ±(99.9%) 0.003 ms/op
Iteration   3: 3.136 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.299 ±(99.9%) 4.259 ms/op [Average]
  (min, avg, max) = (3.136, 3.299, 3.566), stdev = 0.233
  CI (99.9%): [≈ 0, 7.558] (assumes normal distribution)


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
# Warmup Iteration   1: 8.040 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.005 ms/op
Iteration   1: 3.730 ±(99.9%) 0.008 ms/op
Iteration   2: 3.876 ±(99.9%) 0.009 ms/op
Iteration   3: 3.722 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.776 ±(99.9%) 1.583 ms/op [Average]
  (min, avg, max) = (3.722, 3.776, 3.876), stdev = 0.087
  CI (99.9%): [2.193, 5.359] (assumes normal distribution)


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
# Warmup Iteration   1: 9.063 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  13.992 ms/op
                 createUser·p0.9999: 19.826 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  10.383 ms/op
                 createUser·p0.9999: 22.747 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  15.303 ms/op
                 createUser·p0.9999: 21.120 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299890
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18821 
    [ 2.500,  5.000) = 276941 
    [ 5.000,  7.500) = 3185 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     21.726 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 8.128 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
Iteration   1: 3.284 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 23.936 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 18.816 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304817
  mean =      3.151 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27659 
    [ 2.500,  5.000) = 270420 
    [ 5.000,  7.500) = 6066 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     10.733 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 7.295 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
Iteration   1: 3.206 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  18.235 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.379 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  19.020 ms/op
                 getUser·p0.9999: 24.872 ms/op
                 getUser·p1.00:   34.800 ms/op

Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  12.388 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294428
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19153 
    [ 2.500,  5.000) = 267359 
    [ 5.000,  7.500) = 7019 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     27.246 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 9.319 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.010 ms/op
Iteration   1: 3.845 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  15.563 ms/op
                 listUser·p0.9999: 27.132 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 3.673 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.010 ms/op
                 listUser·p0.99:   5.997 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.686 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 14.631 ms/op
                 listUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256937
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 249584 
    [ 5.000,  7.500) = 5379 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.978 ms/op
     p(99.9900) =     25.874 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.988 ± 2.093  ops/ms
ClientPb.existUser                       thrpt       3  10.236 ± 4.140  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 4.976  ops/ms
ClientPb.listUser                        thrpt       3   8.424 ± 1.055  ops/ms
ClientPb.createUser                       avgt       3   3.253 ± 1.018   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 2.559   ms/op
ClientPb.getUser                          avgt       3   3.299 ± 4.259   ms/op
ClientPb.listUser                         avgt       3   3.776 ± 1.583   ms/op
ClientPb.createUser                     sample  299890   3.197 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.726           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.200           ms/op
ClientPb.existUser                      sample  304817   3.151 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.069           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.805           ms/op
ClientPb.getUser                        sample  294428   3.260 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.894           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.022           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.905           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.800           ms/op
ClientPb.listUser                       sample  256937   3.733 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.613           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.874           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
