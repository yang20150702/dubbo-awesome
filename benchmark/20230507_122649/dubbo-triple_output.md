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
# Warmup Iteration   1: 2.620 ops/ms
# Warmup Iteration   2: 6.321 ops/ms
# Warmup Iteration   3: 9.189 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 9.735 ops/ms
Iteration   3: 9.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.778 ±(99.9%) 0.682 ops/ms [Average]
  (min, avg, max) = (9.735, 9.778, 9.801), stdev = 0.037
  CI (99.9%): [9.096, 10.460] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.605 ops/ms
# Warmup Iteration   2: 9.110 ops/ms
# Warmup Iteration   3: 9.960 ops/ms
Iteration   1: 10.425 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.435 ±(99.9%) 0.168 ops/ms [Average]
  (min, avg, max) = (10.425, 10.435, 10.443), stdev = 0.009
  CI (99.9%): [10.267, 10.604] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ops/ms
# Warmup Iteration   2: 8.226 ops/ms
# Warmup Iteration   3: 9.508 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 9.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.096 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (9.958, 10.096, 10.183), stdev = 0.121
  CI (99.9%): [7.893, 12.298] (assumes normal distribution)


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
# Warmup Iteration   1: 3.267 ops/ms
# Warmup Iteration   2: 7.595 ops/ms
# Warmup Iteration   3: 8.513 ops/ms
Iteration   1: 8.548 ops/ms
Iteration   2: 8.581 ops/ms
Iteration   3: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.661 ±(99.9%) 3.077 ops/ms [Average]
  (min, avg, max) = (8.548, 8.661, 8.855), stdev = 0.169
  CI (99.9%): [5.584, 11.739] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.253 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.006 ms/op
Iteration   1: 3.299 ±(99.9%) 0.006 ms/op
Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
Iteration   3: 3.066 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.200 ±(99.9%) 2.196 ms/op [Average]
  (min, avg, max) = (3.066, 3.200, 3.299), stdev = 0.120
  CI (99.9%): [1.004, 5.397] (assumes normal distribution)


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
# Warmup Iteration   1: 6.357 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
Iteration   3: 3.107 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.076 ±(99.9%) 1.252 ms/op [Average]
  (min, avg, max) = (2.998, 3.076, 3.124), stdev = 0.069
  CI (99.9%): [1.825, 4.328] (assumes normal distribution)


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
# Warmup Iteration   1: 7.803 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.004 ms/op
Iteration   1: 3.319 ±(99.9%) 0.004 ms/op
Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
Iteration   3: 3.211 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.246 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.206, 3.246, 3.319), stdev = 0.064
  CI (99.9%): [2.079, 4.412] (assumes normal distribution)


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
# Warmup Iteration   1: 8.664 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.010 ms/op
Iteration   1: 3.827 ±(99.9%) 0.006 ms/op
Iteration   2: 3.714 ±(99.9%) 0.005 ms/op
Iteration   3: 3.927 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.822 ±(99.9%) 1.944 ms/op [Average]
  (min, avg, max) = (3.714, 3.822, 3.927), stdev = 0.107
  CI (99.9%): [1.878, 5.767] (assumes normal distribution)


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
# Warmup Iteration   1: 7.827 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  9.010 ms/op
                 createUser·p0.9999: 18.184 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  18.545 ms/op
                 createUser·p0.9999: 20.188 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 26.437 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301824
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20907 
    [ 2.500,  5.000) = 277072 
    [ 5.000,  7.500) = 3086 
    [ 7.500, 10.000) = 289 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     15.895 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 7.015 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.256 ms/op
                 existUser·p0.9999: 23.484 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.854 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 23.182 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312116
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30559 
    [ 2.500,  5.000) = 278475 
    [ 5.000,  7.500) = 2472 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.363 ms/op
     p(99.0000) =      4.988 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.113 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 8.331 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
Iteration   1: 3.382 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.274 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  18.593 ms/op
                 getUser·p0.9999: 21.088 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.633 ms/op
                 getUser·p0.999:  11.673 ms/op
                 getUser·p0.9999: 23.001 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 21.630 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294013
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21930 
    [ 2.500,  5.000) = 264402 
    [ 5.000,  7.500) = 6793 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.989 ms/op
     p(99.9900) =     22.072 ms/op
     p(99.9990) =     23.333 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 9.374 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.013 ms/op
Iteration   1: 3.900 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.769 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  13.798 ms/op
                 listUser·p0.9999: 15.741 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.818 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 19.878 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250474
  mean =      3.829 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 240728 
    [ 5.000,  7.500) = 7667 
    [ 7.500, 10.000) = 1304 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.778 ± 0.682  ops/ms
ClientPb.existUser                       thrpt       3  10.435 ± 0.168  ops/ms
ClientPb.getUser                         thrpt       3  10.096 ± 2.203  ops/ms
ClientPb.listUser                        thrpt       3   8.661 ± 3.077  ops/ms
ClientPb.createUser                       avgt       3   3.200 ± 2.196   ms/op
ClientPb.existUser                        avgt       3   3.076 ± 1.252   ms/op
ClientPb.getUser                          avgt       3   3.246 ± 1.166   ms/op
ClientPb.listUser                         avgt       3   3.822 ± 1.944   ms/op
ClientPb.createUser                     sample  301824   3.178 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.921           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.895           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.297           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  312116   3.074 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.462           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.379           ms/op
ClientPb.getUser                        sample  294013   3.261 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.989           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.072           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.495           ms/op
ClientPb.listUser                       sample  250474   3.829 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.214           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.530           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.120           ms/op
