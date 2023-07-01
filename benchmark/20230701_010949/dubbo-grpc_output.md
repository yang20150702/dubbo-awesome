# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 5.685 ops/ms
# Warmup Iteration   3: 6.868 ops/ms
Iteration   1: 7.220 ops/ms
Iteration   2: 7.211 ops/ms
Iteration   3: 7.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.238 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (7.211, 7.238, 7.284), stdev = 0.040
  CI (99.9%): [6.512, 7.964] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.815 ops/ms
# Warmup Iteration   2: 7.085 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 7.873 ops/ms
Iteration   3: 7.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.899 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (7.817, 7.899, 8.006), stdev = 0.097
  CI (99.9%): [6.131, 9.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.357 ops/ms
# Warmup Iteration   2: 6.791 ops/ms
# Warmup Iteration   3: 7.141 ops/ms
Iteration   1: 7.002 ops/ms
Iteration   2: 7.013 ops/ms
Iteration   3: 7.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.120 ±(99.9%) 3.540 ops/ms [Average]
  (min, avg, max) = (7.002, 7.120, 7.344), stdev = 0.194
  CI (99.9%): [3.580, 10.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 5.235 ops/ms
# Warmup Iteration   3: 5.519 ops/ms
Iteration   1: 5.511 ops/ms
Iteration   2: 5.555 ops/ms
Iteration   3: 5.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.542 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (5.511, 5.542, 5.561), stdev = 0.027
  CI (99.9%): [5.041, 6.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.411 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.558 ±(99.9%) 0.005 ms/op
Iteration   1: 4.375 ±(99.9%) 0.005 ms/op
Iteration   2: 4.312 ±(99.9%) 0.010 ms/op
Iteration   3: 4.270 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.319 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (4.270, 4.319, 4.375), stdev = 0.053
  CI (99.9%): [3.357, 5.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.160 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.003 ms/op
Iteration   1: 4.231 ±(99.9%) 0.002 ms/op
Iteration   2: 3.897 ±(99.9%) 0.004 ms/op
Iteration   3: 4.192 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.107 ±(99.9%) 3.337 ms/op [Average]
  (min, avg, max) = (3.897, 4.107, 4.231), stdev = 0.183
  CI (99.9%): [0.769, 7.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.771 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.563 ±(99.9%) 0.004 ms/op
Iteration   1: 4.505 ±(99.9%) 0.004 ms/op
Iteration   2: 4.353 ±(99.9%) 0.003 ms/op
Iteration   3: 4.369 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.409 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (4.353, 4.409, 4.505), stdev = 0.083
  CI (99.9%): [2.888, 5.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.244 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.884 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.018 ms/op
Iteration   1: 5.561 ±(99.9%) 0.018 ms/op
Iteration   2: 5.531 ±(99.9%) 0.012 ms/op
Iteration   3: 5.584 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.559 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (5.531, 5.559, 5.584), stdev = 0.026
  CI (99.9%): [5.077, 6.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.557 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.754 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.014 ms/op
Iteration   1: 4.384 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 4.380 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.201 ms/op
                 createUser·p0.999:  15.974 ms/op
                 createUser·p0.9999: 27.637 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 4.372 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.460 ms/op
                 createUser·p0.999:  14.509 ms/op
                 createUser·p0.9999: 29.002 ms/op
                 createUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219112
  mean =      4.379 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5856 
    [ 2.500,  5.000) = 168133 
    [ 5.000,  7.500) = 43356 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.630 ms/op
     p(99.9900) =     28.511 ms/op
     p(99.9990) =     29.118 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.466 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.624 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.011 ms/op
Iteration   1: 4.112 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   4.932 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  11.222 ms/op
                 existUser·p0.9999: 16.391 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   2: 4.048 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.437 ms/op
                 existUser·p0.999:  13.842 ms/op
                 existUser·p0.9999: 22.818 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 4.325 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   7.500 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 27.925 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230829
  mean =      4.158 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8854 
    [ 2.500,  5.000) = 191976 
    [ 5.000,  7.500) = 28135 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     26.373 ms/op
     p(99.9990) =     28.216 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.723 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.013 ms/op
Iteration   1: 4.369 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  12.727 ms/op
                 getUser·p0.9999: 19.171 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 4.315 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  14.509 ms/op
                 getUser·p0.9999: 19.896 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   3: 4.307 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  14.287 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221606
  mean =      4.330 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4808 
    [ 2.500,  5.000) = 179821 
    [ 5.000,  7.500) = 35233 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     14.048 ms/op
     p(99.9900) =     27.842 ms/op
     p(99.9990) =     28.709 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.836 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.217 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.738 ±(99.9%) 0.019 ms/op
Iteration   1: 5.361 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   6.742 ms/op
                 listUser·p0.95:   7.823 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  15.735 ms/op
                 listUser·p0.9999: 19.533 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 5.671 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  18.010 ms/op
                 listUser·p0.9999: 22.809 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 5.702 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.763 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.767 ms/op
                 listUser·p0.999:  18.806 ms/op
                 listUser·p0.9999: 24.622 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172099
  mean =      5.574 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 59820 
    [ 5.000,  7.500) = 98006 
    [ 7.500, 10.000) = 11824 
    [10.000, 12.500) = 1661 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     17.298 ms/op
     p(99.9900) =     23.205 ms/op
     p(99.9990) =     25.053 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.238 ± 0.726  ops/ms
ClientGrpc.existUser                       thrpt       3   7.899 ± 1.768  ops/ms
ClientGrpc.getUser                         thrpt       3   7.120 ± 3.540  ops/ms
ClientGrpc.listUser                        thrpt       3   5.542 ± 0.501  ops/ms
ClientGrpc.createUser                       avgt       3   4.319 ± 0.962   ms/op
ClientGrpc.existUser                        avgt       3   4.107 ± 3.337   ms/op
ClientGrpc.getUser                          avgt       3   4.409 ± 1.521   ms/op
ClientGrpc.listUser                         avgt       3   5.559 ± 0.482   ms/op
ClientGrpc.createUser                     sample  219112   4.379 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.950           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.209           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.630           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.511           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.262           ms/op
ClientGrpc.existUser                      sample  230829   4.158 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.891           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.186           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.644           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.193           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.156           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.373           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.344           ms/op
ClientGrpc.getUser                        sample  221606   4.330 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.147           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.184           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.048           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.842           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  172099   5.574 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.425           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.208           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.298           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.205           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.100           ms/op
