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
# Warmup Iteration   1: 1.972 ops/ms
# Warmup Iteration   2: 5.018 ops/ms
# Warmup Iteration   3: 6.817 ops/ms
Iteration   1: 7.409 ops/ms
Iteration   2: 7.356 ops/ms
Iteration   3: 7.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.400 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (7.356, 7.400, 7.434), stdev = 0.040
  CI (99.9%): [6.674, 8.126] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ops/ms
# Warmup Iteration   2: 7.169 ops/ms
# Warmup Iteration   3: 7.467 ops/ms
Iteration   1: 7.744 ops/ms
Iteration   2: 7.718 ops/ms
Iteration   3: 7.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.690 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (7.609, 7.690, 7.744), stdev = 0.071
  CI (99.9%): [6.387, 8.994] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ops/ms
# Warmup Iteration   2: 6.609 ops/ms
# Warmup Iteration   3: 6.603 ops/ms
Iteration   1: 7.244 ops/ms
Iteration   2: 7.595 ops/ms
Iteration   3: 7.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.351 ±(99.9%) 3.872 ops/ms [Average]
  (min, avg, max) = (7.213, 7.351, 7.595), stdev = 0.212
  CI (99.9%): [3.478, 11.223] (assumes normal distribution)


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
# Warmup Iteration   1: 3.592 ops/ms
# Warmup Iteration   2: 5.083 ops/ms
# Warmup Iteration   3: 5.527 ops/ms
Iteration   1: 5.659 ops/ms
Iteration   2: 5.549 ops/ms
Iteration   3: 5.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.650 ±(99.9%) 1.779 ops/ms [Average]
  (min, avg, max) = (5.549, 5.650, 5.743), stdev = 0.098
  CI (99.9%): [3.871, 7.429] (assumes normal distribution)


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
# Warmup Iteration   1: 7.517 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.102 ±(99.9%) 0.010 ms/op
Iteration   1: 4.628 ±(99.9%) 0.003 ms/op
Iteration   2: 4.376 ±(99.9%) 0.003 ms/op
Iteration   3: 4.333 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.445 ±(99.9%) 2.910 ms/op [Average]
  (min, avg, max) = (4.333, 4.445, 4.628), stdev = 0.159
  CI (99.9%): [1.536, 7.355] (assumes normal distribution)


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
# Warmup Iteration   1: 6.394 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.003 ms/op
Iteration   1: 4.224 ±(99.9%) 0.003 ms/op
Iteration   2: 4.199 ±(99.9%) 0.003 ms/op
Iteration   3: 4.281 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.235 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (4.199, 4.235, 4.281), stdev = 0.042
  CI (99.9%): [3.477, 4.993] (assumes normal distribution)


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
# Warmup Iteration   1: 6.233 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.550 ±(99.9%) 0.004 ms/op
Iteration   1: 4.414 ±(99.9%) 0.005 ms/op
Iteration   2: 4.441 ±(99.9%) 0.002 ms/op
Iteration   3: 4.484 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.446 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (4.414, 4.446, 4.484), stdev = 0.035
  CI (99.9%): [3.801, 5.092] (assumes normal distribution)


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
# Warmup Iteration   1: 9.538 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 6.054 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.638 ±(99.9%) 0.011 ms/op
Iteration   1: 5.402 ±(99.9%) 0.008 ms/op
Iteration   2: 5.772 ±(99.9%) 0.030 ms/op
Iteration   3: 5.497 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.557 ±(99.9%) 3.507 ms/op [Average]
  (min, avg, max) = (5.402, 5.557, 5.772), stdev = 0.192
  CI (99.9%): [2.049, 9.064] (assumes normal distribution)


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
# Warmup Iteration   1: 6.794 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.416 ±(99.9%) 0.013 ms/op
Iteration   1: 4.385 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  13.810 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 4.355 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  11.790 ms/op
                 createUser·p0.9999: 18.589 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 4.390 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219452
  mean =      4.377 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5355 
    [ 2.500,  5.000) = 168171 
    [ 5.000,  7.500) = 43923 
    [ 7.500, 10.000) = 1542 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     12.790 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     29.236 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.578 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.529 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.508 ±(99.9%) 0.015 ms/op
Iteration   1: 4.314 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  13.568 ms/op
                 existUser·p0.9999: 16.592 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 4.223 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  12.606 ms/op
                 existUser·p0.9999: 18.724 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   3: 4.242 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  13.025 ms/op
                 existUser·p0.9999: 23.051 ms/op
                 existUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225541
  mean =      4.259 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6221 
    [ 2.500,  5.000) = 183207 
    [ 5.000,  7.500) = 32959 
    [ 7.500, 10.000) = 2330 
    [10.000, 12.500) = 572 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     12.991 ms/op
     p(99.9900) =     22.275 ms/op
     p(99.9990) =     23.363 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 6.232 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.771 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.440 ±(99.9%) 0.014 ms/op
Iteration   1: 4.310 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.636 ms/op
                 getUser·p0.999:  12.343 ms/op
                 getUser·p0.9999: 29.032 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 4.388 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.351 ms/op
                 getUser·p0.999:  10.003 ms/op
                 getUser·p0.9999: 25.470 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  9.642 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222528
  mean =      4.311 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6786 
    [ 2.500,  5.000) = 177442 
    [ 5.000,  7.500) = 36335 
    [ 7.500, 10.000) = 1640 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     30.893 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 8.181 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.185 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.784 ±(99.9%) 0.021 ms/op
Iteration   1: 5.459 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.840 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  16.480 ms/op
                 listUser·p0.9999: 21.056 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 5.467 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.553 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.174 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 21.445 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 5.604 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.349 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  18.215 ms/op
                 listUser·p0.9999: 22.442 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174130
  mean =      5.509 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 64340 
    [ 5.000,  7.500) = 96846 
    [ 7.500, 10.000) = 10779 
    [10.000, 12.500) = 1449 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     21.548 ms/op
     p(99.9990) =     22.677 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.400 ± 0.726  ops/ms
ClientGrpc.existUser                       thrpt       3   7.690 ± 1.303  ops/ms
ClientGrpc.getUser                         thrpt       3   7.351 ± 3.872  ops/ms
ClientGrpc.listUser                        thrpt       3   5.650 ± 1.779  ops/ms
ClientGrpc.createUser                       avgt       3   4.445 ± 2.910   ms/op
ClientGrpc.existUser                        avgt       3   4.235 ± 0.758   ms/op
ClientGrpc.getUser                          avgt       3   4.446 ± 0.646   ms/op
ClientGrpc.listUser                         avgt       3   5.557 ± 3.507   ms/op
ClientGrpc.createUser                     sample  219452   4.377 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.925           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.923           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.389           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.790           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.869           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.426           ms/op
ClientGrpc.existUser                      sample  225541   4.259 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.984           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.349           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.069           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.991           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.275           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.593           ms/op
ClientGrpc.getUser                        sample  222528   4.311 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.862           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.393           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.293           ms/op
ClientGrpc.listUser                       sample  174130   5.509 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.553           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.036           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.289           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.548           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
