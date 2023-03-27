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
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 6.938 ops/ms
# Warmup Iteration   3: 8.423 ops/ms
Iteration   1: 8.789 ops/ms
Iteration   2: 8.982 ops/ms
Iteration   3: 8.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.866 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (8.789, 8.866, 8.982), stdev = 0.102
  CI (99.9%): [7.002, 10.730] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.932 ops/ms
# Warmup Iteration   2: 8.980 ops/ms
# Warmup Iteration   3: 9.211 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.541 ops/ms
Iteration   3: 9.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.472 ±(99.9%) 1.651 ops/ms [Average]
  (min, avg, max) = (9.369, 9.472, 9.541), stdev = 0.091
  CI (99.9%): [7.821, 11.123] (assumes normal distribution)


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
# Warmup Iteration   1: 5.726 ops/ms
# Warmup Iteration   2: 8.656 ops/ms
# Warmup Iteration   3: 8.957 ops/ms
Iteration   1: 9.001 ops/ms
Iteration   2: 8.940 ops/ms
Iteration   3: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.001 ±(99.9%) 1.126 ops/ms [Average]
  (min, avg, max) = (8.940, 9.001, 9.063), stdev = 0.062
  CI (99.9%): [7.875, 10.127] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.963 ops/ms
# Warmup Iteration   2: 6.109 ops/ms
# Warmup Iteration   3: 6.753 ops/ms
Iteration   1: 6.631 ops/ms
Iteration   2: 6.772 ops/ms
Iteration   3: 6.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.773 ±(99.9%) 2.585 ops/ms [Average]
  (min, avg, max) = (6.631, 6.773, 6.915), stdev = 0.142
  CI (99.9%): [4.188, 9.358] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.956 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.003 ms/op
Iteration   1: 3.651 ±(99.9%) 0.004 ms/op
Iteration   2: 3.575 ±(99.9%) 0.003 ms/op
Iteration   3: 3.602 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.609 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.575, 3.609, 3.651), stdev = 0.039
  CI (99.9%): [2.901, 4.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.747 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.003 ms/op
Iteration   1: 3.797 ±(99.9%) 0.003 ms/op
Iteration   2: 3.308 ±(99.9%) 0.003 ms/op
Iteration   3: 3.324 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.476 ±(99.9%) 5.066 ms/op [Average]
  (min, avg, max) = (3.308, 3.476, 3.797), stdev = 0.278
  CI (99.9%): [≈ 0, 8.542] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.927 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.572 ±(99.9%) 0.011 ms/op
Iteration   1: 3.663 ±(99.9%) 0.004 ms/op
Iteration   2: 3.530 ±(99.9%) 0.005 ms/op
Iteration   3: 3.566 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.586 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.530, 3.586, 3.663), stdev = 0.069
  CI (99.9%): [2.329, 4.843] (assumes normal distribution)


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
# Warmup Iteration   1: 6.392 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.021 ms/op
Iteration   1: 4.672 ±(99.9%) 0.013 ms/op
Iteration   2: 4.623 ±(99.9%) 0.015 ms/op
Iteration   3: 4.641 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.645 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (4.623, 4.645, 4.672), stdev = 0.025
  CI (99.9%): [4.186, 5.105] (assumes normal distribution)


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
Iteration   1: 3.573 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.052 ms/op
                 createUser·p0.9999: 15.827 ms/op
                 createUser·p1.00:   16.269 ms/op

Iteration   2: 3.600 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  8.090 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.643 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  11.844 ms/op
                 createUser·p0.9999: 19.209 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266309
  mean =      3.605 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5732 
    [ 2.500,  5.000) = 255052 
    [ 5.000,  7.500) = 4880 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     19.697 ms/op
     p(99.9990) =     21.700 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.006 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  7.043 ms/op
                 existUser·p0.9999: 14.493 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 3.419 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  7.373 ms/op
                 existUser·p0.9999: 14.187 ms/op
                 existUser·p1.00:   16.417 ms/op

Iteration   3: 3.416 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  12.065 ms/op
                 existUser·p0.9999: 20.194 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279306
  mean =      3.437 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6677 
    [ 2.500,  5.000) = 269222 
    [ 5.000,  7.500) = 3039 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      8.083 ms/op
     p(99.9900) =     19.246 ms/op
     p(99.9990) =     20.618 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.358 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.007 ms/op
Iteration   1: 3.540 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  8.922 ms/op
                 getUser·p0.9999: 22.181 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   2: 3.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.200 ms/op
                 getUser·p0.999:  7.619 ms/op
                 getUser·p0.9999: 14.700 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.598 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 22.089 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268854
  mean =      3.570 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7195 
    [ 2.500,  5.000) = 256915 
    [ 5.000,  7.500) = 4327 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.473 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     22.522 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 6.039 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.119 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.012 ms/op
Iteration   1: 4.669 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.767 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  14.984 ms/op
                 listUser·p0.9999: 23.931 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 4.609 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  16.191 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 4.747 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  21.681 ms/op
                 listUser·p0.9999: 28.454 ms/op
                 listUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205162
  mean =      4.674 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 165019 
    [ 5.000,  7.500) = 35775 
    [ 7.500, 10.000) = 3354 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.546 ms/op
     p(95.0000) =      6.431 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     17.029 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     29.027 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.866 ± 1.864  ops/ms
ClientGrpc.existUser                       thrpt       3   9.472 ± 1.651  ops/ms
ClientGrpc.getUser                         thrpt       3   9.001 ± 1.126  ops/ms
ClientGrpc.listUser                        thrpt       3   6.773 ± 2.585  ops/ms
ClientGrpc.createUser                       avgt       3   3.609 ± 0.708   ms/op
ClientGrpc.existUser                        avgt       3   3.476 ± 5.066   ms/op
ClientGrpc.getUser                          avgt       3   3.586 ± 1.257   ms/op
ClientGrpc.listUser                         avgt       3   4.645 ± 0.459   ms/op
ClientGrpc.createUser                     sample  266309   3.605 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.741           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.697           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  279306   3.437 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.965           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.083           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.246           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.677           ms/op
ClientGrpc.getUser                        sample  268854   3.570 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.824           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.149           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.431           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.473           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.922           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  205162   4.674 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.178           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.029           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.575           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.131           ms/op
