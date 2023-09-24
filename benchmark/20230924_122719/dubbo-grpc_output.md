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
# Warmup Iteration   1: 1.945 ops/ms
# Warmup Iteration   2: 5.231 ops/ms
# Warmup Iteration   3: 6.535 ops/ms
Iteration   1: 7.154 ops/ms
Iteration   2: 7.324 ops/ms
Iteration   3: 6.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.094 ±(99.9%) 4.852 ops/ms [Average]
  (min, avg, max) = (6.803, 7.094, 7.324), stdev = 0.266
  CI (99.9%): [2.241, 11.946] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.729 ops/ms
# Warmup Iteration   2: 6.653 ops/ms
# Warmup Iteration   3: 7.170 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 7.479 ops/ms
Iteration   3: 7.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.490 ±(99.9%) 3.994 ops/ms [Average]
  (min, avg, max) = (7.277, 7.490, 7.715), stdev = 0.219
  CI (99.9%): [3.496, 11.484] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.196 ops/ms
# Warmup Iteration   2: 6.566 ops/ms
# Warmup Iteration   3: 6.932 ops/ms
Iteration   1: 7.032 ops/ms
Iteration   2: 7.329 ops/ms
Iteration   3: 6.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.119 ±(99.9%) 3.333 ops/ms [Average]
  (min, avg, max) = (6.996, 7.119, 7.329), stdev = 0.183
  CI (99.9%): [3.786, 10.452] (assumes normal distribution)


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
# Warmup Iteration   1: 3.525 ops/ms
# Warmup Iteration   2: 4.908 ops/ms
# Warmup Iteration   3: 5.490 ops/ms
Iteration   1: 5.662 ops/ms
Iteration   2: 5.693 ops/ms
Iteration   3: 5.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.724 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (5.662, 5.724, 5.818), stdev = 0.083
  CI (99.9%): [4.218, 7.230] (assumes normal distribution)


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
# Warmup Iteration   1: 6.965 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.798 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.011 ms/op
Iteration   1: 4.459 ±(99.9%) 0.003 ms/op
Iteration   2: 4.476 ±(99.9%) 0.003 ms/op
Iteration   3: 4.428 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.455 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (4.428, 4.455, 4.476), stdev = 0.024
  CI (99.9%): [4.012, 4.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.622 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.639 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.398 ±(99.9%) 0.004 ms/op
Iteration   1: 4.266 ±(99.9%) 0.002 ms/op
Iteration   2: 4.301 ±(99.9%) 0.004 ms/op
Iteration   3: 4.381 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.316 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (4.266, 4.316, 4.381), stdev = 0.059
  CI (99.9%): [3.238, 5.395] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.225 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.595 ±(99.9%) 0.004 ms/op
Iteration   1: 4.690 ±(99.9%) 0.003 ms/op
Iteration   2: 4.636 ±(99.9%) 0.004 ms/op
Iteration   3: 4.612 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.646 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (4.612, 4.646, 4.690), stdev = 0.040
  CI (99.9%): [3.919, 5.372] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 6.213 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.023 ms/op
Iteration   1: 5.758 ±(99.9%) 0.015 ms/op
Iteration   2: 5.685 ±(99.9%) 0.027 ms/op
Iteration   3: 5.526 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.656 ±(99.9%) 2.163 ms/op [Average]
  (min, avg, max) = (5.526, 5.656, 5.758), stdev = 0.119
  CI (99.9%): [3.493, 7.819] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.339 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.530 ±(99.9%) 0.014 ms/op
Iteration   1: 4.565 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   7.950 ms/op
                 createUser·p0.999:  11.516 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 4.430 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 28.170 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 4.372 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 22.043 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 215407
  mean =      4.454 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1744 
    [ 2.500,  5.000) = 167138 
    [ 5.000,  7.500) = 44479 
    [ 7.500, 10.000) = 1509 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     28.924 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 6.610 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.013 ms/op
Iteration   1: 4.348 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   7.643 ms/op
                 existUser·p0.999:  12.900 ms/op
                 existUser·p0.9999: 16.673 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 4.163 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   6.914 ms/op
                 existUser·p0.999:  11.095 ms/op
                 existUser·p0.9999: 20.763 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   3: 4.240 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   4.125 ms/op
                 existUser·p0.90:   5.243 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   8.118 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 20.495 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 225821
  mean =      4.249 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5290 
    [ 2.500,  5.000) = 186727 
    [ 5.000,  7.500) = 31481 
    [ 7.500, 10.000) = 1731 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     11.717 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     21.324 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 7.348 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.555 ±(99.9%) 0.013 ms/op
Iteration   1: 4.480 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 16.508 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 4.486 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  12.457 ms/op
                 getUser·p0.9999: 17.140 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 4.582 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.816 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  19.077 ms/op
                 getUser·p0.9999: 35.127 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 212643
  mean =      4.516 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3732 
    [ 2.500,  5.000) = 161014 
    [ 5.000,  7.500) = 44833 
    [ 7.500, 10.000) = 2224 
    [10.000, 12.500) = 517 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     13.649 ms/op
     p(99.9900) =     33.522 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 7.988 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.371 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.860 ±(99.9%) 0.022 ms/op
Iteration   1: 5.743 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   10.750 ms/op
                 listUser·p0.999:  18.829 ms/op
                 listUser·p0.9999: 22.165 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 5.716 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  18.286 ms/op
                 listUser·p0.9999: 23.709 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   3: 5.794 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 36.732 ms/op
                 listUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166805
  mean =      5.751 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 51732 
    [ 5.000,  7.500) = 97213 
    [ 7.500, 10.000) = 14555 
    [10.000, 12.500) = 2432 
    [12.500, 15.000) = 435 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     19.227 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     37.486 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.094 ± 4.852  ops/ms
ClientGrpc.existUser                       thrpt       3   7.490 ± 3.994  ops/ms
ClientGrpc.getUser                         thrpt       3   7.119 ± 3.333  ops/ms
ClientGrpc.listUser                        thrpt       3   5.724 ± 1.506  ops/ms
ClientGrpc.createUser                       avgt       3   4.455 ± 0.443   ms/op
ClientGrpc.existUser                        avgt       3   4.316 ± 1.079   ms/op
ClientGrpc.getUser                          avgt       3   4.646 ± 0.726   ms/op
ClientGrpc.listUser                         avgt       3   5.656 ± 2.163   ms/op
ClientGrpc.createUser                     sample  215407   4.454 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.513           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.906           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.009           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.230           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.000           ms/op
ClientGrpc.existUser                      sample  225821   4.249 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.920           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.545           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.717           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.382           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.217           ms/op
ClientGrpc.getUser                        sample  212643   4.516 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.059           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.649           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.522           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.586           ms/op
ClientGrpc.listUser                       sample  166805   5.751 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.823           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.610           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.684           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.026           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.227           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.586           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.749           ms/op
