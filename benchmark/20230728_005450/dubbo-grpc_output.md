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
# Warmup Iteration   1: 2.256 ops/ms
# Warmup Iteration   2: 5.341 ops/ms
# Warmup Iteration   3: 6.754 ops/ms
Iteration   1: 7.269 ops/ms
Iteration   2: 7.196 ops/ms
Iteration   3: 7.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.242 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (7.196, 7.242, 7.269), stdev = 0.041
  CI (99.9%): [6.501, 7.984] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.509 ops/ms
# Warmup Iteration   2: 6.974 ops/ms
# Warmup Iteration   3: 7.409 ops/ms
Iteration   1: 7.666 ops/ms
Iteration   2: 7.701 ops/ms
Iteration   3: 7.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.751 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (7.666, 7.751, 7.886), stdev = 0.118
  CI (99.9%): [5.598, 9.904] (assumes normal distribution)


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
# Warmup Iteration   1: 4.450 ops/ms
# Warmup Iteration   2: 6.655 ops/ms
# Warmup Iteration   3: 7.120 ops/ms
Iteration   1: 7.487 ops/ms
Iteration   2: 7.263 ops/ms
Iteration   3: 7.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.319 ±(99.9%) 2.706 ops/ms [Average]
  (min, avg, max) = (7.207, 7.319, 7.487), stdev = 0.148
  CI (99.9%): [4.613, 10.025] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.379 ops/ms
# Warmup Iteration   2: 5.095 ops/ms
# Warmup Iteration   3: 5.428 ops/ms
Iteration   1: 5.515 ops/ms
Iteration   2: 5.594 ops/ms
Iteration   3: 5.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.579 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (5.515, 5.579, 5.627), stdev = 0.058
  CI (99.9%): [4.530, 6.628] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.247 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.736 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.528 ±(99.9%) 0.007 ms/op
Iteration   1: 4.546 ±(99.9%) 0.003 ms/op
Iteration   2: 4.453 ±(99.9%) 0.003 ms/op
Iteration   3: 4.418 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.472 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (4.418, 4.472, 4.546), stdev = 0.066
  CI (99.9%): [3.269, 5.675] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.344 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.009 ms/op
Iteration   1: 4.084 ±(99.9%) 0.003 ms/op
Iteration   2: 4.168 ±(99.9%) 0.004 ms/op
Iteration   3: 4.237 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.163 ±(99.9%) 1.404 ms/op [Average]
  (min, avg, max) = (4.084, 4.163, 4.237), stdev = 0.077
  CI (99.9%): [2.759, 5.567] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.897 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.713 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.531 ±(99.9%) 0.010 ms/op
Iteration   1: 4.370 ±(99.9%) 0.003 ms/op
Iteration   2: 4.425 ±(99.9%) 0.004 ms/op
Iteration   3: 4.401 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.399 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (4.370, 4.399, 4.425), stdev = 0.028
  CI (99.9%): [3.895, 4.903] (assumes normal distribution)


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
# Warmup Iteration   1: 8.716 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 6.281 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.790 ±(99.9%) 0.019 ms/op
Iteration   1: 5.611 ±(99.9%) 0.006 ms/op
Iteration   2: 5.748 ±(99.9%) 0.013 ms/op
Iteration   3: 5.603 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.654 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (5.603, 5.654, 5.748), stdev = 0.081
  CI (99.9%): [4.172, 7.136] (assumes normal distribution)


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
# Warmup Iteration   1: 6.968 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.794 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.550 ±(99.9%) 0.014 ms/op
Iteration   1: 4.556 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   5.784 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  15.646 ms/op
                 createUser·p0.9999: 22.478 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 4.502 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.494 ms/op
                 createUser·p0.999:  10.826 ms/op
                 createUser·p0.9999: 21.689 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 4.453 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  12.110 ms/op
                 createUser·p0.9999: 28.377 ms/op
                 createUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 213147
  mean =      4.503 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3246 
    [ 2.500,  5.000) = 159145 
    [ 5.000,  7.500) = 48455 
    [ 7.500, 10.000) = 1744 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     27.177 ms/op
     p(99.9990) =     31.014 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.012 ms/op
Iteration   1: 4.182 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.333 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  16.025 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 4.105 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.481 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 19.445 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   3: 4.258 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229544
  mean =      4.181 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6341 
    [ 2.500,  5.000) = 194427 
    [ 5.000,  7.500) = 27488 
    [ 7.500, 10.000) = 985 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     11.089 ms/op
     p(99.9900) =     20.645 ms/op
     p(99.9990) =     22.197 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.170 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.822 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.012 ms/op
Iteration   1: 4.510 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  15.372 ms/op
                 getUser·p0.9999: 18.669 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 4.424 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.326 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 19.424 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   3: 4.463 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   7.558 ms/op
                 getUser·p0.999:  12.261 ms/op
                 getUser·p0.9999: 20.951 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214804
  mean =      4.465 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3738 
    [ 2.500,  5.000) = 164155 
    [ 5.000,  7.500) = 44749 
    [ 7.500, 10.000) = 1530 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     19.547 ms/op
     p(99.9990) =     21.393 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 8.467 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.505 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.020 ms/op
Iteration   1: 5.251 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.635 ms/op
                 listUser·p0.99:   9.977 ms/op
                 listUser·p0.999:  17.174 ms/op
                 listUser·p0.9999: 28.988 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   2: 5.681 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.323 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 25.947 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   3: 5.617 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  19.355 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174130
  mean =      5.510 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 60600 
    [ 5.000,  7.500) = 101828 
    [ 7.500, 10.000) = 9814 
    [10.000, 12.500) = 1284 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.898 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     28.331 ms/op
     p(99.9990) =     29.608 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.242 ± 0.741  ops/ms
ClientGrpc.existUser                       thrpt       3   7.751 ± 2.153  ops/ms
ClientGrpc.getUser                         thrpt       3   7.319 ± 2.706  ops/ms
ClientGrpc.listUser                        thrpt       3   5.579 ± 1.049  ops/ms
ClientGrpc.createUser                       avgt       3   4.472 ± 1.203   ms/op
ClientGrpc.existUser                        avgt       3   4.163 ± 1.404   ms/op
ClientGrpc.getUser                          avgt       3   4.399 ± 0.504   ms/op
ClientGrpc.listUser                         avgt       3   5.654 ± 1.482   ms/op
ClientGrpc.createUser                     sample  213147   4.503 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.844           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.595           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.021           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.643           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.177           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.162           ms/op
ClientGrpc.existUser                      sample  229544   4.181 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.900           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.717           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.089           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.645           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.379           ms/op
ClientGrpc.getUser                        sample  214804   4.465 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.116           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.898           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.512           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.091           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.547           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  174130   5.510 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.341           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.547           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.331           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.753           ms/op
