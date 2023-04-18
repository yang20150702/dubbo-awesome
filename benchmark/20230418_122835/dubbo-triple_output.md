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
# Warmup Iteration   1: 2.142 ops/ms
# Warmup Iteration   2: 5.232 ops/ms
# Warmup Iteration   3: 8.534 ops/ms
Iteration   1: 9.244 ops/ms
Iteration   2: 9.128 ops/ms
Iteration   3: 8.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.088 ±(99.9%) 3.273 ops/ms [Average]
  (min, avg, max) = (8.892, 9.088, 9.244), stdev = 0.179
  CI (99.9%): [5.815, 12.360] (assumes normal distribution)


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
# Warmup Iteration   1: 3.081 ops/ms
# Warmup Iteration   2: 9.215 ops/ms
# Warmup Iteration   3: 9.734 ops/ms
Iteration   1: 9.960 ops/ms
Iteration   2: 9.745 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.820 ±(99.9%) 2.214 ops/ms [Average]
  (min, avg, max) = (9.745, 9.820, 9.960), stdev = 0.121
  CI (99.9%): [7.605, 12.034] (assumes normal distribution)


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
# Warmup Iteration   1: 3.299 ops/ms
# Warmup Iteration   2: 8.444 ops/ms
# Warmup Iteration   3: 9.028 ops/ms
Iteration   1: 9.382 ops/ms
Iteration   2: 9.484 ops/ms
Iteration   3: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.325 ±(99.9%) 3.529 ops/ms [Average]
  (min, avg, max) = (9.109, 9.325, 9.484), stdev = 0.193
  CI (99.9%): [5.796, 12.854] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 7.079 ops/ms
# Warmup Iteration   3: 7.701 ops/ms
Iteration   1: 7.973 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.907 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (7.825, 7.907, 7.973), stdev = 0.075
  CI (99.9%): [6.541, 9.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.192 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.005 ms/op
Iteration   1: 3.406 ±(99.9%) 0.007 ms/op
Iteration   2: 3.833 ±(99.9%) 0.009 ms/op
Iteration   3: 3.334 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.525 ±(99.9%) 4.924 ms/op [Average]
  (min, avg, max) = (3.334, 3.525, 3.833), stdev = 0.270
  CI (99.9%): [≈ 0, 8.449] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.314 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.006 ms/op
Iteration   1: 3.229 ±(99.9%) 0.005 ms/op
Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
Iteration   3: 3.215 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.222 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.215, 3.222, 3.229), stdev = 0.007
  CI (99.9%): [3.093, 3.351] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.739 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.006 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
Iteration   2: 3.448 ±(99.9%) 0.004 ms/op
Iteration   3: 3.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.424 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.369, 3.424, 3.457), stdev = 0.049
  CI (99.9%): [2.539, 4.310] (assumes normal distribution)


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
# Warmup Iteration   1: 11.501 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.977 ±(99.9%) 0.006 ms/op
Iteration   2: 3.866 ±(99.9%) 0.013 ms/op
Iteration   3: 3.893 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.912 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (3.866, 3.912, 3.977), stdev = 0.058
  CI (99.9%): [2.854, 4.970] (assumes normal distribution)


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
# Warmup Iteration   1: 9.367 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.011 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  20.900 ms/op
                 createUser·p0.9999: 26.789 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  22.211 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 26.212 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279073
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10860 
    [ 2.500,  5.000) = 261439 
    [ 5.000,  7.500) = 5559 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 101 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     27.430 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 8.198 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
Iteration   1: 3.231 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 22.777 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.301 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.446 ms/op
                 existUser·p0.999:  11.488 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.431 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  26.345 ms/op
                 existUser·p0.9999: 28.508 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289259
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9135 
    [ 2.500,  5.000) = 274521 
    [ 5.000,  7.500) = 4711 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     28.117 ms/op
     p(99.9990) =     29.385 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 9.853 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.469 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  20.708 ms/op
                 getUser·p0.9999: 23.447 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.390 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  22.544 ms/op
                 getUser·p0.9999: 25.654 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.343 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  19.246 ms/op
                 getUser·p0.9999: 25.540 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282331
  mean =      3.400 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6873 
    [ 2.500,  5.000) = 266677 
    [ 5.000,  7.500) = 7648 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     19.650 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     27.059 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 9.707 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.014 ms/op
Iteration   1: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  18.057 ms/op
                 listUser·p0.9999: 25.192 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.904 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 16.269 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.963 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   8.046 ms/op
                 listUser·p0.999:  15.980 ms/op
                 listUser·p0.9999: 19.003 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244557
  mean =      3.925 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 235692 
    [ 5.000,  7.500) = 6534 
    [ 7.500, 10.000) = 1242 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.719 ms/op
     p(99.9900) =     23.498 ms/op
     p(99.9990) =     25.544 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.088 ± 3.273  ops/ms
ClientPb.existUser                       thrpt       3   9.820 ± 2.214  ops/ms
ClientPb.getUser                         thrpt       3   9.325 ± 3.529  ops/ms
ClientPb.listUser                        thrpt       3   7.907 ± 1.366  ops/ms
ClientPb.createUser                       avgt       3   3.525 ± 4.924   ms/op
ClientPb.existUser                        avgt       3   3.222 ± 0.129   ms/op
ClientPb.getUser                          avgt       3   3.424 ± 0.885   ms/op
ClientPb.listUser                         avgt       3   3.912 ± 1.058   ms/op
ClientPb.createUser                     sample  279073   3.438 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.692           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.444           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.984           ms/op
ClientPb.existUser                      sample  289259   3.319 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.167           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.878           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  282331   3.400 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.038           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.650           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.330           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.427           ms/op
ClientPb.listUser                       sample  244557   3.925 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.491           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.719           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.498           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
