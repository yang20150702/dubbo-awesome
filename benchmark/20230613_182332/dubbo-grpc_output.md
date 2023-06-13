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
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 6.310 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.489 ops/ms
Iteration   2: 8.644 ops/ms
Iteration   3: 8.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.504 ±(99.9%) 2.430 ops/ms [Average]
  (min, avg, max) = (8.379, 8.504, 8.644), stdev = 0.133
  CI (99.9%): [6.074, 10.934] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.898 ops/ms
# Warmup Iteration   2: 8.163 ops/ms
# Warmup Iteration   3: 8.996 ops/ms
Iteration   1: 8.925 ops/ms
Iteration   2: 8.907 ops/ms
Iteration   3: 9.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.046 ±(99.9%) 4.100 ops/ms [Average]
  (min, avg, max) = (8.907, 9.046, 9.305), stdev = 0.225
  CI (99.9%): [4.946, 13.145] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 8.080 ops/ms
# Warmup Iteration   3: 8.486 ops/ms
Iteration   1: 8.512 ops/ms
Iteration   2: 8.764 ops/ms
Iteration   3: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.614 ±(99.9%) 2.419 ops/ms [Average]
  (min, avg, max) = (8.512, 8.614, 8.764), stdev = 0.133
  CI (99.9%): [6.195, 11.034] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ops/ms
# Warmup Iteration   2: 5.809 ops/ms
# Warmup Iteration   3: 6.548 ops/ms
Iteration   1: 6.656 ops/ms
Iteration   2: 6.756 ops/ms
Iteration   3: 6.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.696 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (6.656, 6.696, 6.756), stdev = 0.053
  CI (99.9%): [5.733, 7.660] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.238 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.003 ms/op
Iteration   1: 3.777 ±(99.9%) 0.003 ms/op
Iteration   2: 3.708 ±(99.9%) 0.003 ms/op
Iteration   3: 3.707 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.730 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.707, 3.730, 3.777), stdev = 0.040
  CI (99.9%): [2.997, 4.464] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.225 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.003 ms/op
Iteration   1: 3.589 ±(99.9%) 0.005 ms/op
Iteration   2: 3.483 ±(99.9%) 0.002 ms/op
Iteration   3: 3.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.500 ±(99.9%) 1.505 ms/op [Average]
  (min, avg, max) = (3.427, 3.500, 3.589), stdev = 0.082
  CI (99.9%): [1.995, 5.005] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.004 ms/op
Iteration   1: 3.865 ±(99.9%) 0.003 ms/op
Iteration   2: 3.777 ±(99.9%) 0.004 ms/op
Iteration   3: 3.645 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.762 ±(99.9%) 2.018 ms/op [Average]
  (min, avg, max) = (3.645, 3.762, 3.865), stdev = 0.111
  CI (99.9%): [1.744, 5.781] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.074 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.011 ms/op
Iteration   1: 4.641 ±(99.9%) 0.008 ms/op
Iteration   2: 4.619 ±(99.9%) 0.015 ms/op
Iteration   3: 4.695 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.652 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (4.619, 4.652, 4.695), stdev = 0.039
  CI (99.9%): [3.940, 5.364] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.288 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.008 ms/op
Iteration   1: 3.628 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   2: 3.587 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.543 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  11.507 ms/op
                 createUser·p0.9999: 16.254 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   3: 3.605 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  9.376 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266001
  mean =      3.607 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8570 
    [ 2.500,  5.000) = 250557 
    [ 5.000,  7.500) = 6131 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     21.345 ms/op
     p(99.9990) =     22.109 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.726 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.008 ms/op
Iteration   1: 3.522 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.554 ms/op
                 existUser·p0.9999: 16.938 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 3.429 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.425 ms/op
                 existUser·p0.9999: 16.543 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   3: 3.579 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  12.663 ms/op
                 existUser·p0.9999: 35.590 ms/op
                 existUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273509
  mean =      3.509 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7619 
    [ 2.500,  5.000) = 260721 
    [ 5.000,  7.500) = 4472 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.363 ms/op
     p(99.9900) =     35.039 ms/op
     p(99.9990) =     36.062 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.389 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.009 ms/op
Iteration   1: 3.628 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  13.573 ms/op
                 getUser·p0.9999: 16.390 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 3.614 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 15.256 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   3: 3.607 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  7.869 ms/op
                 getUser·p0.9999: 20.255 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265462
  mean =      3.616 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7939 
    [ 2.500,  5.000) = 251493 
    [ 5.000,  7.500) = 5462 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     10.101 ms/op
     p(99.9900) =     19.872 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.936 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.983 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.015 ms/op
Iteration   1: 4.679 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.972 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.383 ms/op
                 listUser·p0.999:  14.132 ms/op
                 listUser·p0.9999: 17.536 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 4.747 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  16.263 ms/op
                 listUser·p0.9999: 18.990 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 4.683 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 23.297 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204244
  mean =      4.703 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 525 
    [ 2.500,  5.000) = 157441 
    [ 5.000,  7.500) = 40644 
    [ 7.500, 10.000) = 4828 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     15.934 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     24.738 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.504 ± 2.430  ops/ms
ClientGrpc.existUser                       thrpt       3   9.046 ± 4.100  ops/ms
ClientGrpc.getUser                         thrpt       3   8.614 ± 2.419  ops/ms
ClientGrpc.listUser                        thrpt       3   6.696 ± 0.963  ops/ms
ClientGrpc.createUser                       avgt       3   3.730 ± 0.733   ms/op
ClientGrpc.existUser                        avgt       3   3.500 ± 1.505   ms/op
ClientGrpc.getUser                          avgt       3   3.762 ± 2.018   ms/op
ClientGrpc.listUser                         avgt       3   4.652 ± 0.712   ms/op
ClientGrpc.createUser                     sample  266001   3.607 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.957           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.841           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.633           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.345           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.315           ms/op
ClientGrpc.existUser                      sample  273509   3.509 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.805           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.096           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.363           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.039           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.110           ms/op
ClientGrpc.getUser                        sample  265462   3.616 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.820           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.101           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.872           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.578           ms/op
ClientGrpc.listUser                       sample  204244   4.703 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.260           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.934           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.791           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
