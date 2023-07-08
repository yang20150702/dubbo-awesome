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
# Warmup Iteration   1: 2.567 ops/ms
# Warmup Iteration   2: 6.088 ops/ms
# Warmup Iteration   3: 9.328 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.677 ±(99.9%) 2.585 ops/ms [Average]
  (min, avg, max) = (9.528, 9.677, 9.810), stdev = 0.142
  CI (99.9%): [7.092, 12.263] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.398 ops/ms
# Warmup Iteration   2: 9.234 ops/ms
# Warmup Iteration   3: 9.847 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 9.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.916 ±(99.9%) 5.884 ops/ms [Average]
  (min, avg, max) = (9.547, 9.916, 10.147), stdev = 0.323
  CI (99.9%): [4.032, 15.800] (assumes normal distribution)


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
# Warmup Iteration   1: 3.368 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 9.150 ops/ms
Iteration   1: 10.220 ops/ms
Iteration   2: 9.904 ops/ms
Iteration   3: 9.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.022 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (9.904, 10.022, 10.220), stdev = 0.172
  CI (99.9%): [6.883, 13.161] (assumes normal distribution)


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
# Warmup Iteration   1: 3.275 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 8.452 ops/ms
Iteration   1: 8.347 ops/ms
Iteration   2: 8.650 ops/ms
Iteration   3: 8.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.510 ±(99.9%) 2.795 ops/ms [Average]
  (min, avg, max) = (8.347, 8.510, 8.650), stdev = 0.153
  CI (99.9%): [5.715, 11.306] (assumes normal distribution)


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
# Warmup Iteration   1: 9.135 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.003 ms/op
Iteration   1: 3.219 ±(99.9%) 0.004 ms/op
Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.207 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.124, 3.207, 3.277), stdev = 0.077
  CI (99.9%): [1.799, 4.614] (assumes normal distribution)


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
# Warmup Iteration   1: 7.745 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.005 ms/op
Iteration   1: 3.050 ±(99.9%) 0.009 ms/op
Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.029 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.997, 3.029, 3.050), stdev = 0.028
  CI (99.9%): [2.516, 3.542] (assumes normal distribution)


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
# Warmup Iteration   1: 8.028 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.004 ms/op
Iteration   1: 3.339 ±(99.9%) 0.003 ms/op
Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
Iteration   3: 3.283 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 2.224 ms/op [Average]
  (min, avg, max) = (3.106, 3.243, 3.339), stdev = 0.122
  CI (99.9%): [1.018, 5.467] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.575 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.007 ms/op
Iteration   1: 3.720 ±(99.9%) 0.008 ms/op
Iteration   2: 3.678 ±(99.9%) 0.009 ms/op
Iteration   3: 3.701 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.699 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.678, 3.699, 3.720), stdev = 0.021
  CI (99.9%): [3.314, 4.085] (assumes normal distribution)


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
# Warmup Iteration   1: 7.725 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.010 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  15.471 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  14.440 ms/op
                 createUser·p0.9999: 25.022 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.864 ms/op
                 createUser·p0.999:  19.602 ms/op
                 createUser·p0.9999: 22.529 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296615
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21452 
    [ 2.500,  5.000) = 269631 
    [ 5.000,  7.500) = 4754 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     19.063 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.237 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 7.646 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  13.287 ms/op
                 existUser·p0.9999: 23.770 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.123 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  12.855 ms/op
                 existUser·p0.9999: 24.765 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.697 ms/op
                 existUser·p0.999:  8.686 ms/op
                 existUser·p0.9999: 28.217 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307262
  mean =      3.122 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20723 
    [ 2.500,  5.000) = 280809 
    [ 5.000,  7.500) = 4946 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     12.701 ms/op
     p(99.9900) =     26.518 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 7.965 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
Iteration   1: 3.284 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  15.133 ms/op
                 getUser·p0.9999: 25.273 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.146 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.778 ms/op
                 getUser·p0.999:  20.556 ms/op
                 getUser·p0.9999: 24.210 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   3: 3.281 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  9.183 ms/op
                 getUser·p0.9999: 21.635 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296466
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27027 
    [ 2.500,  5.000) = 262607 
    [ 5.000,  7.500) = 5742 
    [ 7.500, 10.000) = 721 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     23.977 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.314 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.419 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.014 ms/op
Iteration   1: 3.718 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.870 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 20.460 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.711 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.971 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 3.796 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.209 ms/op
                 listUser·p0.9999: 22.508 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256540
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 248373 
    [ 5.000,  7.500) = 6300 
    [ 7.500, 10.000) = 1129 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.225 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.677 ± 2.585  ops/ms
ClientPb.existUser                       thrpt       3   9.916 ± 5.884  ops/ms
ClientPb.getUser                         thrpt       3  10.022 ± 3.139  ops/ms
ClientPb.listUser                        thrpt       3   8.510 ± 2.795  ops/ms
ClientPb.createUser                       avgt       3   3.207 ± 1.408   ms/op
ClientPb.existUser                        avgt       3   3.029 ± 0.513   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 2.224   ms/op
ClientPb.listUser                         avgt       3   3.699 ± 0.385   ms/op
ClientPb.createUser                     sample  296615   3.233 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.063           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.478           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.411           ms/op
ClientPb.existUser                      sample  307262   3.122 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.701           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.518           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.770           ms/op
ClientPb.getUser                        sample  296466   3.235 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.041           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.977           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  256540   3.741 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.487           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.451           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.527           ms/op
