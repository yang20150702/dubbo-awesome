# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 5.660 ops/ms
# Warmup Iteration   3: 7.177 ops/ms
Iteration   1: 7.139 ops/ms
Iteration   2: 7.346 ops/ms
Iteration   3: 7.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.347 ±(99.9%) 3.821 ops/ms [Average]
  (min, avg, max) = (7.139, 7.347, 7.557), stdev = 0.209
  CI (99.9%): [3.526, 11.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 7.080 ops/ms
# Warmup Iteration   3: 7.282 ops/ms
Iteration   1: 7.492 ops/ms
Iteration   2: 7.772 ops/ms
Iteration   3: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.797 ±(99.9%) 5.817 ops/ms [Average]
  (min, avg, max) = (7.492, 7.797, 8.128), stdev = 0.319
  CI (99.9%): [1.980, 13.615] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ops/ms
# Warmup Iteration   2: 6.684 ops/ms
# Warmup Iteration   3: 7.084 ops/ms
Iteration   1: 7.284 ops/ms
Iteration   2: 7.294 ops/ms
Iteration   3: 7.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.288 ±(99.9%) 0.092 ops/ms [Average]
  (min, avg, max) = (7.284, 7.288, 7.294), stdev = 0.005
  CI (99.9%): [7.195, 7.380] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ops/ms
# Warmup Iteration   2: 5.159 ops/ms
# Warmup Iteration   3: 5.647 ops/ms
Iteration   1: 5.707 ops/ms
Iteration   2: 5.679 ops/ms
Iteration   3: 5.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.763 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (5.679, 5.763, 5.902), stdev = 0.122
  CI (99.9%): [3.542, 7.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.449 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.380 ±(99.9%) 0.003 ms/op
Iteration   1: 4.408 ±(99.9%) 0.003 ms/op
Iteration   2: 4.268 ±(99.9%) 0.002 ms/op
Iteration   3: 4.239 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.305 ±(99.9%) 1.648 ms/op [Average]
  (min, avg, max) = (4.239, 4.305, 4.408), stdev = 0.090
  CI (99.9%): [2.657, 5.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.869 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.004 ms/op
Iteration   1: 4.182 ±(99.9%) 0.004 ms/op
Iteration   2: 4.210 ±(99.9%) 0.001 ms/op
Iteration   3: 4.086 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.159 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (4.086, 4.159, 4.210), stdev = 0.065
  CI (99.9%): [2.973, 5.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.571 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.553 ±(99.9%) 0.003 ms/op
Iteration   1: 4.483 ±(99.9%) 0.002 ms/op
Iteration   2: 4.437 ±(99.9%) 0.005 ms/op
Iteration   3: 4.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.474 ±(99.9%) 0.625 ms/op [Average]
  (min, avg, max) = (4.437, 4.474, 4.504), stdev = 0.034
  CI (99.9%): [3.850, 5.099] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.352 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.990 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.757 ±(99.9%) 0.013 ms/op
Iteration   1: 5.421 ±(99.9%) 0.021 ms/op
Iteration   2: 5.528 ±(99.9%) 0.017 ms/op
Iteration   3: 5.601 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.517 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (5.421, 5.517, 5.601), stdev = 0.091
  CI (99.9%): [3.866, 7.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.902 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.011 ms/op
Iteration   1: 4.301 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.358 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  13.926 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 4.699 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  17.763 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   35.717 ms/op

Iteration   3: 4.446 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  16.947 ms/op
                 createUser·p0.9999: 23.488 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214137
  mean =      4.476 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3209 
    [ 2.500,  5.000) = 159881 
    [ 5.000,  7.500) = 48445 
    [ 7.500, 10.000) = 1914 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     16.731 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.033 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.011 ms/op
Iteration   1: 4.067 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  10.688 ms/op
                 existUser·p0.9999: 16.025 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   2: 4.032 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  12.256 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   3: 4.029 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 19.139 ms/op
                 existUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237317
  mean =      4.043 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 4599 
    [ 2.500,  3.750) = 82829 
    [ 3.750,  5.000) = 128721 
    [ 5.000,  6.250) = 17701 
    [ 6.250,  7.500) = 1927 
    [ 7.500,  8.750) = 704 
    [ 8.750, 10.000) = 363 
    [10.000, 11.250) = 195 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     11.021 ms/op
     p(99.9900) =     17.671 ms/op
     p(99.9990) =     19.407 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.100 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.691 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.013 ms/op
Iteration   1: 4.440 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   8.192 ms/op
                 getUser·p0.999:  13.222 ms/op
                 getUser·p0.9999: 19.772 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 4.475 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  12.870 ms/op
                 getUser·p0.9999: 21.917 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 4.359 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  14.332 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216843
  mean =      4.424 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2624 
    [ 2.500,  5.000) = 173052 
    [ 5.000,  7.500) = 38397 
    [ 7.500, 10.000) = 1984 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     13.290 ms/op
     p(99.9900) =     25.012 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.003 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.611 ±(99.9%) 0.020 ms/op
Iteration   1: 5.521 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  20.747 ms/op
                 listUser·p0.9999: 24.531 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 5.668 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  21.947 ms/op
                 listUser·p0.9999: 29.232 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   3: 5.611 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  26.182 ms/op
                 listUser·p0.9999: 30.245 ms/op
                 listUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171328
  mean =      5.599 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 56354 
    [ 5.000,  7.500) = 101275 
    [ 7.500, 10.000) = 11263 
    [10.000, 12.500) = 1720 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     29.454 ms/op
     p(99.9990) =     30.432 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.347 ± 3.821  ops/ms
ClientGrpc.existUser                       thrpt       3   7.797 ± 5.817  ops/ms
ClientGrpc.getUser                         thrpt       3   7.288 ± 0.092  ops/ms
ClientGrpc.listUser                        thrpt       3   5.763 ± 2.221  ops/ms
ClientGrpc.createUser                       avgt       3   4.305 ± 1.648   ms/op
ClientGrpc.existUser                        avgt       3   4.159 ± 1.187   ms/op
ClientGrpc.getUser                          avgt       3   4.474 ± 0.625   ms/op
ClientGrpc.listUser                         avgt       3   5.517 ± 1.651   ms/op
ClientGrpc.createUser                     sample  214137   4.476 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.902           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.731           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.180           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.717           ms/op
ClientGrpc.existUser                      sample  237317   4.043 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.957           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.709           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.671           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.694           ms/op
ClientGrpc.getUser                        sample  216843   4.424 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.830           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.889           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.290           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.012           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  171328   5.599 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.021           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.420           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.987           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.454           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.573           ms/op
