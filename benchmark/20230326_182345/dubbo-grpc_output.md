# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.317 ops/ms
# Warmup Iteration   2: 7.141 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.123 ±(99.9%) 6.586 ops/ms [Average]
  (min, avg, max) = (8.707, 9.123, 9.335), stdev = 0.361
  CI (99.9%): [2.538, 15.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ops/ms
# Warmup Iteration   2: 8.797 ops/ms
# Warmup Iteration   3: 9.354 ops/ms
Iteration   1: 9.283 ops/ms
Iteration   2: 9.498 ops/ms
Iteration   3: 9.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.412 ±(99.9%) 2.073 ops/ms [Average]
  (min, avg, max) = (9.283, 9.412, 9.498), stdev = 0.114
  CI (99.9%): [7.339, 11.485] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.526 ops/ms
# Warmup Iteration   2: 8.547 ops/ms
# Warmup Iteration   3: 9.131 ops/ms
Iteration   1: 9.093 ops/ms
Iteration   2: 8.850 ops/ms
Iteration   3: 8.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.977 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (8.850, 8.977, 9.093), stdev = 0.121
  CI (99.9%): [6.762, 11.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.516 ops/ms
# Warmup Iteration   2: 6.636 ops/ms
# Warmup Iteration   3: 7.080 ops/ms
Iteration   1: 7.214 ops/ms
Iteration   2: 6.959 ops/ms
Iteration   3: 6.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.056 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (6.959, 7.056, 7.214), stdev = 0.138
  CI (99.9%): [4.534, 9.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.060 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.010 ms/op
Iteration   1: 3.629 ±(99.9%) 0.012 ms/op
Iteration   2: 3.704 ±(99.9%) 0.004 ms/op
Iteration   3: 3.670 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.668 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (3.629, 3.668, 3.704), stdev = 0.037
  CI (99.9%): [2.985, 4.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.624 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.004 ms/op
Iteration   1: 3.537 ±(99.9%) 0.003 ms/op
Iteration   2: 3.522 ±(99.9%) 0.003 ms/op
Iteration   3: 3.361 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.473 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (3.361, 3.473, 3.537), stdev = 0.097
  CI (99.9%): [1.698, 5.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.080 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.004 ms/op
Iteration   1: 3.868 ±(99.9%) 0.003 ms/op
Iteration   2: 3.776 ±(99.9%) 0.004 ms/op
Iteration   3: 3.626 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.757 ±(99.9%) 2.230 ms/op [Average]
  (min, avg, max) = (3.626, 3.757, 3.868), stdev = 0.122
  CI (99.9%): [1.527, 5.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.211 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.781 ±(99.9%) 0.016 ms/op
Iteration   1: 4.769 ±(99.9%) 0.012 ms/op
Iteration   2: 4.946 ±(99.9%) 0.019 ms/op
Iteration   3: 4.762 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.826 ±(99.9%) 1.901 ms/op [Average]
  (min, avg, max) = (4.762, 4.826, 4.946), stdev = 0.104
  CI (99.9%): [2.924, 6.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.512 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.010 ms/op
Iteration   1: 3.704 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  11.463 ms/op
                 createUser·p0.9999: 15.554 ms/op
                 createUser·p1.00:   16.908 ms/op

Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  12.452 ms/op
                 createUser·p0.9999: 17.357 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   3: 3.775 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.157 ms/op
                 createUser·p0.999:  14.226 ms/op
                 createUser·p0.9999: 21.087 ms/op
                 createUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254265
  mean =      3.775 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7491 
    [ 2.500,  5.000) = 232967 
    [ 5.000,  7.500) = 11770 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     18.551 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.999 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.010 ms/op
Iteration   1: 3.691 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  10.814 ms/op
                 existUser·p0.9999: 17.247 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.557 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.622 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.994 ms/op
                 existUser·p0.999:  10.852 ms/op
                 existUser·p0.9999: 22.883 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265025
  mean =      3.623 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11239 
    [ 2.500,  5.000) = 242361 
    [ 5.000,  7.500) = 9915 
    [ 7.500, 10.000) = 1197 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.321 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.254 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
Iteration   1: 3.661 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.565 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 15.586 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 3.706 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  9.700 ms/op
                 getUser·p0.9999: 19.685 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   3: 3.687 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.714 ms/op
                 getUser·p0.999:  11.878 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260418
  mean =      3.685 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11362 
    [ 2.500,  5.000) = 237757 
    [ 5.000,  7.500) = 9807 
    [ 7.500, 10.000) = 1099 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     11.839 ms/op
     p(99.9900) =     33.553 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.514 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.128 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.016 ms/op
Iteration   1: 4.784 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 18.152 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 4.795 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  16.999 ms/op
                 listUser·p0.9999: 19.944 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.640 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  22.029 ms/op
                 listUser·p0.9999: 33.627 ms/op
                 listUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202494
  mean =      4.739 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 600 
    [ 2.500,  5.000) = 155909 
    [ 5.000,  7.500) = 40076 
    [ 7.500, 10.000) = 4953 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     16.392 ms/op
     p(99.9900) =     32.760 ms/op
     p(99.9990) =     34.010 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.123 ± 6.586  ops/ms
ClientGrpc.existUser                       thrpt       3   9.412 ± 2.073  ops/ms
ClientGrpc.getUser                         thrpt       3   8.977 ± 2.215  ops/ms
ClientGrpc.listUser                        thrpt       3   7.056 ± 2.523  ops/ms
ClientGrpc.createUser                       avgt       3   3.668 ± 0.683   ms/op
ClientGrpc.existUser                        avgt       3   3.473 ± 1.775   ms/op
ClientGrpc.getUser                          avgt       3   3.757 ± 2.230   ms/op
ClientGrpc.listUser                         avgt       3   4.826 ± 1.901   ms/op
ClientGrpc.createUser                     sample  254265   3.775 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.135           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.960           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.551           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.168           ms/op
ClientGrpc.existUser                      sample  265025   3.623 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.387           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.577           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.462           ms/op
ClientGrpc.getUser                        sample  260418   3.685 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.963           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.455           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.839           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.553           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.800           ms/op
ClientGrpc.listUser                       sample  202494   4.739 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.247           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.392           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.760           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.144           ms/op
