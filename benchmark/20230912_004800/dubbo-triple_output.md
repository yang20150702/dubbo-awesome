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
# Warmup Iteration   1: 2.427 ops/ms
# Warmup Iteration   2: 5.788 ops/ms
# Warmup Iteration   3: 8.865 ops/ms
Iteration   1: 9.345 ops/ms
Iteration   2: 9.669 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.593 ±(99.9%) 4.016 ops/ms [Average]
  (min, avg, max) = (9.345, 9.593, 9.765), stdev = 0.220
  CI (99.9%): [5.576, 13.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 8.995 ops/ms
# Warmup Iteration   3: 9.798 ops/ms
Iteration   1: 10.118 ops/ms
Iteration   2: 10.143 ops/ms
Iteration   3: 10.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.103 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (10.046, 10.103, 10.143), stdev = 0.050
  CI (99.9%): [9.186, 11.019] (assumes normal distribution)


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
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 9.316 ops/ms
Iteration   1: 9.986 ops/ms
Iteration   2: 10.050 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.943 ±(99.9%) 2.442 ops/ms [Average]
  (min, avg, max) = (9.793, 9.943, 10.050), stdev = 0.134
  CI (99.9%): [7.501, 12.385] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.090 ops/ms
# Warmup Iteration   2: 7.732 ops/ms
# Warmup Iteration   3: 8.033 ops/ms
Iteration   1: 8.333 ops/ms
Iteration   2: 8.198 ops/ms
Iteration   3: 8.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.210 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (8.099, 8.210, 8.333), stdev = 0.118
  CI (99.9%): [6.066, 10.354] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.331 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.006 ms/op
Iteration   1: 3.339 ±(99.9%) 0.006 ms/op
Iteration   2: 3.294 ±(99.9%) 0.004 ms/op
Iteration   3: 3.461 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.365 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.294, 3.365, 3.461), stdev = 0.087
  CI (99.9%): [1.786, 4.944] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.893 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.002 ms/op
Iteration   1: 3.211 ±(99.9%) 0.003 ms/op
Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
Iteration   3: 3.255 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.184 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (3.085, 3.184, 3.255), stdev = 0.088
  CI (99.9%): [1.571, 4.796] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.853 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.004 ms/op
Iteration   1: 3.270 ±(99.9%) 0.004 ms/op
Iteration   2: 3.303 ±(99.9%) 0.003 ms/op
Iteration   3: 3.263 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.279 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (3.263, 3.279, 3.303), stdev = 0.022
  CI (99.9%): [2.881, 3.676] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.926 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.006 ms/op
Iteration   1: 3.851 ±(99.9%) 0.008 ms/op
Iteration   2: 3.897 ±(99.9%) 0.004 ms/op
Iteration   3: 3.894 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.881 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.851, 3.881, 3.897), stdev = 0.026
  CI (99.9%): [3.410, 4.352] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.972 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  15.464 ms/op
                 createUser·p0.9999: 20.304 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.206 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  22.033 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   4.205 ms/op
                 createUser·p0.99:   5.941 ms/op
                 createUser·p0.999:  15.450 ms/op
                 createUser·p0.9999: 20.035 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294460
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22017 
    [ 2.500,  5.000) = 265761 
    [ 5.000,  7.500) = 5120 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.139 ms/op
     p(99.9000) =     17.155 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     25.310 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 7.585 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
Iteration   1: 3.255 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.939 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  12.472 ms/op
                 existUser·p0.9999: 21.469 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   6.088 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 23.904 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.311 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  9.402 ms/op
                 existUser·p0.9999: 21.605 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294515
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27653 
    [ 2.500,  5.000) = 258130 
    [ 5.000,  7.500) = 7490 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     10.608 ms/op
     p(99.9900) =     22.464 ms/op
     p(99.9990) =     24.745 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 8.772 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.011 ms/op
Iteration   1: 3.370 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  18.912 ms/op
                 getUser·p0.9999: 24.708 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  10.678 ms/op
                 getUser·p0.9999: 22.974 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.737 ms/op
                 getUser·p0.9999: 22.695 ms/op
                 getUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291486
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8419 
    [ 2.500,  5.000) = 275851 
    [ 5.000,  7.500) = 5673 
    [ 7.500, 10.000) = 1066 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     23.780 ms/op
     p(99.9990) =     25.633 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.953 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.013 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.363 ms/op
                 listUser·p0.999:  15.802 ms/op
                 listUser·p0.9999: 23.034 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.769 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  12.307 ms/op
                 listUser·p0.9999: 15.581 ms/op
                 listUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251323
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 242341 
    [ 5.000,  7.500) = 6435 
    [ 7.500, 10.000) = 1774 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     14.871 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.593 ± 4.016  ops/ms
ClientPb.existUser                       thrpt       3  10.103 ± 0.916  ops/ms
ClientPb.getUser                         thrpt       3   9.943 ± 2.442  ops/ms
ClientPb.listUser                        thrpt       3   8.210 ± 2.144  ops/ms
ClientPb.createUser                       avgt       3   3.365 ± 1.579   ms/op
ClientPb.existUser                        avgt       3   3.184 ± 1.612   ms/op
ClientPb.getUser                          avgt       3   3.279 ± 0.397   ms/op
ClientPb.listUser                         avgt       3   3.881 ± 0.471   ms/op
ClientPb.createUser                     sample  294460   3.262 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.389           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.139           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.155           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.921           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.657           ms/op
ClientPb.existUser                      sample  294515   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.763           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.608           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.464           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.904           ms/op
ClientPb.getUser                        sample  291486   3.291 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.253           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.597           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.780           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  251323   3.817 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.980           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.871           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.020           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
