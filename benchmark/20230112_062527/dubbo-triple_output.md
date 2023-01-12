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
# Warmup Iteration   1: 2.497 ops/ms
# Warmup Iteration   2: 6.071 ops/ms
# Warmup Iteration   3: 8.847 ops/ms
Iteration   1: 9.543 ops/ms
Iteration   2: 9.732 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.760 ±(99.9%) 4.250 ops/ms [Average]
  (min, avg, max) = (9.543, 9.760, 10.006), stdev = 0.233
  CI (99.9%): [5.510, 14.010] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 9.310 ops/ms
# Warmup Iteration   3: 10.043 ops/ms
Iteration   1: 10.518 ops/ms
Iteration   2: 10.301 ops/ms
Iteration   3: 10.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.322 ±(99.9%) 3.411 ops/ms [Average]
  (min, avg, max) = (10.146, 10.322, 10.518), stdev = 0.187
  CI (99.9%): [6.911, 13.733] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 9.128 ops/ms
Iteration   1: 10.097 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.827 ±(99.9%) 7.355 ops/ms [Average]
  (min, avg, max) = (9.364, 9.827, 10.097), stdev = 0.403
  CI (99.9%): [2.472, 17.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ops/ms
# Warmup Iteration   2: 8.007 ops/ms
# Warmup Iteration   3: 8.509 ops/ms
Iteration   1: 8.750 ops/ms
Iteration   2: 8.438 ops/ms
Iteration   3: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.595 ±(99.9%) 2.843 ops/ms [Average]
  (min, avg, max) = (8.438, 8.595, 8.750), stdev = 0.156
  CI (99.9%): [5.752, 11.438] (assumes normal distribution)


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
# Warmup Iteration   1: 7.305 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.002 ms/op
Iteration   1: 3.156 ±(99.9%) 0.006 ms/op
Iteration   2: 3.129 ±(99.9%) 0.005 ms/op
Iteration   3: 3.086 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.124 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (3.086, 3.124, 3.156), stdev = 0.035
  CI (99.9%): [2.482, 3.765] (assumes normal distribution)


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
# Warmup Iteration   1: 7.330 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
Iteration   3: 3.141 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.091 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.025, 3.091, 3.141), stdev = 0.060
  CI (99.9%): [2.001, 4.181] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.288 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.002 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.001 ms/op
Iteration   3: 3.275 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.167 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.101, 3.167, 3.275), stdev = 0.094
  CI (99.9%): [1.448, 4.886] (assumes normal distribution)


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
# Warmup Iteration   1: 9.403 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.012 ms/op
Iteration   1: 3.758 ±(99.9%) 0.008 ms/op
Iteration   2: 3.740 ±(99.9%) 0.005 ms/op
Iteration   3: 3.757 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.751 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (3.740, 3.751, 3.758), stdev = 0.010
  CI (99.9%): [3.565, 3.937] (assumes normal distribution)


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
# Warmup Iteration   1: 7.759 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  18.306 ms/op
                 createUser·p0.9999: 20.898 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  13.435 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  15.827 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306932
  mean =      3.126 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25502 
    [ 2.500,  5.000) = 276788 
    [ 5.000,  7.500) = 3763 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     16.434 ms/op
     p(99.9900) =     22.718 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 7.662 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 21.023 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  11.687 ms/op
                 existUser·p0.9999: 21.898 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  13.468 ms/op
                 existUser·p0.9999: 20.009 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308814
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30961 
    [ 2.500,  5.000) = 272782 
    [ 5.000,  7.500) = 4320 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     21.500 ms/op
     p(99.9990) =     22.175 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 7.318 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
Iteration   1: 3.206 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  12.258 ms/op
                 getUser·p0.9999: 22.185 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.299 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  11.910 ms/op
                 getUser·p0.9999: 32.778 ms/op
                 getUser·p1.00:   33.751 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  9.946 ms/op
                 getUser·p0.9999: 21.525 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298543
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7198 
    [ 2.500,  5.000) = 282724 
    [ 5.000,  7.500) = 7561 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     30.620 ms/op
     p(99.9990) =     33.199 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 9.551 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.013 ms/op
Iteration   1: 3.769 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.064 ms/op
                 listUser·p0.9999: 25.909 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 3.751 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.725 ms/op
                 listUser·p0.9999: 21.600 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 3.727 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  11.605 ms/op
                 listUser·p0.9999: 16.155 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255928
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 248679 
    [ 5.000,  7.500) = 5532 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     14.079 ms/op
     p(99.9900) =     24.111 ms/op
     p(99.9990) =     26.262 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.760 ± 4.250  ops/ms
ClientPb.existUser                       thrpt       3  10.322 ± 3.411  ops/ms
ClientPb.getUser                         thrpt       3   9.827 ± 7.355  ops/ms
ClientPb.listUser                        thrpt       3   8.595 ± 2.843  ops/ms
ClientPb.createUser                       avgt       3   3.124 ± 0.642   ms/op
ClientPb.existUser                        avgt       3   3.091 ± 1.090   ms/op
ClientPb.getUser                          avgt       3   3.167 ± 1.719   ms/op
ClientPb.listUser                         avgt       3   3.751 ± 0.186   ms/op
ClientPb.createUser                     sample  306932   3.126 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.434           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.718           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  308814   3.106 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.544           ms/op
ClientPb.getUser                        sample  298543   3.216 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.906           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.255           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.620           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  255928   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.079           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
