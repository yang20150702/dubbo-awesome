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
# Warmup Iteration   1: 3.292 ops/ms
# Warmup Iteration   2: 7.005 ops/ms
# Warmup Iteration   3: 8.455 ops/ms
Iteration   1: 8.786 ops/ms
Iteration   2: 8.887 ops/ms
Iteration   3: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.843 ±(99.9%) 0.945 ops/ms [Average]
  (min, avg, max) = (8.786, 8.843, 8.887), stdev = 0.052
  CI (99.9%): [7.898, 9.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.249 ops/ms
# Warmup Iteration   2: 9.340 ops/ms
# Warmup Iteration   3: 9.206 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 9.636 ops/ms
Iteration   3: 9.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.651 ±(99.9%) 5.689 ops/ms [Average]
  (min, avg, max) = (9.347, 9.651, 9.970), stdev = 0.312
  CI (99.9%): [3.962, 15.340] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.022 ops/ms
# Warmup Iteration   2: 9.024 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.244 ±(99.9%) 2.804 ops/ms [Average]
  (min, avg, max) = (9.121, 9.244, 9.416), stdev = 0.154
  CI (99.9%): [6.440, 12.048] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.071 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 7.062 ops/ms
Iteration   1: 7.367 ops/ms
Iteration   2: 7.254 ops/ms
Iteration   3: 7.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.273 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (7.196, 7.273, 7.367), stdev = 0.087
  CI (99.9%): [5.688, 8.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.943 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.003 ms/op
Iteration   1: 3.562 ±(99.9%) 0.002 ms/op
Iteration   2: 3.462 ±(99.9%) 0.003 ms/op
Iteration   3: 3.382 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.469 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (3.382, 3.469, 3.562), stdev = 0.091
  CI (99.9%): [1.817, 5.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.003 ms/op
Iteration   1: 3.330 ±(99.9%) 0.002 ms/op
Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
Iteration   3: 3.246 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.267 ±(99.9%) 1.023 ms/op [Average]
  (min, avg, max) = (3.224, 3.267, 3.330), stdev = 0.056
  CI (99.9%): [2.244, 4.290] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.919 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.002 ms/op
Iteration   1: 3.569 ±(99.9%) 0.003 ms/op
Iteration   2: 3.348 ±(99.9%) 0.002 ms/op
Iteration   3: 3.478 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.465 ±(99.9%) 2.034 ms/op [Average]
  (min, avg, max) = (3.348, 3.465, 3.569), stdev = 0.111
  CI (99.9%): [1.431, 5.498] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.579 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.023 ms/op
Iteration   1: 4.499 ±(99.9%) 0.018 ms/op
Iteration   2: 4.356 ±(99.9%) 0.016 ms/op
Iteration   3: 5.139 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.665 ±(99.9%) 7.608 ms/op [Average]
  (min, avg, max) = (4.356, 4.665, 5.139), stdev = 0.417
  CI (99.9%): [≈ 0, 12.272] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.938 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 5.626 ±(99.9%) 0.137 ms/op
# Warmup Iteration   3: 5.208 ±(99.9%) 0.129 ms/op
Iteration   1: 4.188 ±(99.9%) 0.089 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   32.857 ms/op
                 createUser·p0.999:  118.187 ms/op
                 createUser·p0.9999: 156.609 ms/op
                 createUser·p1.00:   161.219 ms/op

Iteration   2: 3.483 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 42.994 ms/op
                 createUser·p1.00:   58.130 ms/op

Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.271 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 34.133 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259998
  mean =      3.691 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 258634 
    [ 12.500,  25.000) = 406 
    [ 25.000,  37.500) = 202 
    [ 37.500,  50.000) = 157 
    [ 50.000,  62.500) = 219 
    [ 62.500,  75.000) = 141 
    [ 75.000,  87.500) = 86 
    [ 87.500, 100.000) = 28 
    [100.000, 112.500) = 33 
    [112.500, 125.000) = 29 
    [125.000, 137.500) = 29 
    [137.500, 150.000) = 13 
    [150.000, 162.500) = 21 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     73.007 ms/op
     p(99.9900) =    146.014 ms/op
     p(99.9990) =    160.222 ms/op
     p(99.9999) =    161.219 ms/op
    p(100.0000) =    161.219 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  11.399 ms/op
                 existUser·p0.9999: 13.087 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  12.145 ms/op
                 existUser·p0.9999: 17.387 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   3: 3.260 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.251 ms/op
                 existUser·p0.999:  10.140 ms/op
                 existUser·p0.9999: 28.875 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 292418
  mean =      3.282 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35219 
    [ 2.500,  5.000) = 248818 
    [ 5.000,  7.500) = 7318 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     11.970 ms/op
     p(99.9900) =     27.583 ms/op
     p(99.9990) =     31.329 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
Iteration   1: 3.320 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.912 ms/op
                 getUser·p0.999:  9.869 ms/op
                 getUser·p0.9999: 21.115 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.427 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 26.620 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 3.368 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  9.174 ms/op
                 getUser·p0.9999: 18.743 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 284688
  mean =      3.371 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26302 
    [ 2.500,  5.000) = 249737 
    [ 5.000,  7.500) = 7698 
    [ 7.500, 10.000) = 732 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =      9.606 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     27.081 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.216 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.886 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.633 ±(99.9%) 0.017 ms/op
Iteration   1: 4.501 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   5.956 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.334 ms/op
                 listUser·p0.9999: 21.558 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 4.396 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  20.390 ms/op
                 listUser·p0.9999: 30.015 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   3: 4.451 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  19.073 ms/op
                 listUser·p0.9999: 25.028 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 215774
  mean =      4.449 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1726 
    [ 2.500,  5.000) = 171135 
    [ 5.000,  7.500) = 38209 
    [ 7.500, 10.000) = 3860 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     18.864 ms/op
     p(99.9900) =     29.519 ms/op
     p(99.9990) =     30.174 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt    Score   Error   Units
ClientGrpc.createUser                      thrpt       3    8.843 ± 0.945  ops/ms
ClientGrpc.existUser                       thrpt       3    9.651 ± 5.689  ops/ms
ClientGrpc.getUser                         thrpt       3    9.244 ± 2.804  ops/ms
ClientGrpc.listUser                        thrpt       3    7.273 ± 1.584  ops/ms
ClientGrpc.createUser                       avgt       3    3.469 ± 1.651   ms/op
ClientGrpc.existUser                        avgt       3    3.267 ± 1.023   ms/op
ClientGrpc.getUser                          avgt       3    3.465 ± 2.034   ms/op
ClientGrpc.listUser                         avgt       3    4.665 ± 7.608   ms/op
ClientGrpc.createUser                     sample  259998    3.691 ± 0.027   ms/op
ClientGrpc.createUser:createUser·p0.00    sample            0.702           ms/op
ClientGrpc.createUser:createUser·p0.50    sample            3.387           ms/op
ClientGrpc.createUser:createUser·p0.90    sample            4.309           ms/op
ClientGrpc.createUser:createUser·p0.95    sample            4.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample            7.676           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           73.007           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          146.014           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          161.219           ms/op
ClientGrpc.existUser                      sample  292418    3.282 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample            0.732           ms/op
ClientGrpc.existUser:existUser·p0.50      sample            3.240           ms/op
ClientGrpc.existUser:existUser·p0.90      sample            4.133           ms/op
ClientGrpc.existUser:existUser·p0.95      sample            4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample            6.046           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           11.970           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample           27.583           ms/op
ClientGrpc.existUser:existUser·p1.00      sample           31.425           ms/op
ClientGrpc.getUser                        sample  284688    3.371 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample            0.782           ms/op
ClientGrpc.getUser:getUser·p0.50          sample            3.310           ms/op
ClientGrpc.getUser:getUser·p0.90          sample            4.227           ms/op
ClientGrpc.getUser:getUser·p0.95          sample            4.653           ms/op
ClientGrpc.getUser:getUser·p0.99          sample            6.128           ms/op
ClientGrpc.getUser:getUser·p0.999         sample            9.606           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample           25.330           ms/op
ClientGrpc.getUser:getUser·p1.00          sample           27.394           ms/op
ClientGrpc.listUser                       sample  215774    4.449 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample            0.984           ms/op
ClientGrpc.listUser:listUser·p0.50        sample            4.219           ms/op
ClientGrpc.listUser:listUser·p0.90        sample            5.906           ms/op
ClientGrpc.listUser:listUser·p0.95        sample            6.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample            8.331           ms/op
ClientGrpc.listUser:listUser·p0.999       sample           18.864           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample           29.519           ms/op
ClientGrpc.listUser:listUser·p1.00        sample           30.179           ms/op
