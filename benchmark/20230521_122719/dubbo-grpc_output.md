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
# Warmup Iteration   1: 3.338 ops/ms
# Warmup Iteration   2: 7.158 ops/ms
# Warmup Iteration   3: 8.516 ops/ms
Iteration   1: 8.926 ops/ms
Iteration   2: 8.944 ops/ms
Iteration   3: 8.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.901 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (8.833, 8.901, 8.944), stdev = 0.060
  CI (99.9%): [7.807, 9.995] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.942 ops/ms
# Warmup Iteration   2: 8.888 ops/ms
# Warmup Iteration   3: 9.356 ops/ms
Iteration   1: 9.410 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.418 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (9.393, 9.418, 9.453), stdev = 0.031
  CI (99.9%): [8.855, 9.982] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 8.807 ops/ms
Iteration   2: 9.006 ops/ms
Iteration   3: 8.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.902 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (8.807, 8.902, 9.006), stdev = 0.100
  CI (99.9%): [7.078, 10.727] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.414 ops/ms
# Warmup Iteration   2: 6.396 ops/ms
# Warmup Iteration   3: 6.683 ops/ms
Iteration   1: 6.699 ops/ms
Iteration   2: 6.717 ops/ms
Iteration   3: 6.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.711 ±(99.9%) 0.187 ops/ms [Average]
  (min, avg, max) = (6.699, 6.711, 6.717), stdev = 0.010
  CI (99.9%): [6.524, 6.899] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.243 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.004 ms/op
Iteration   1: 3.609 ±(99.9%) 0.003 ms/op
Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
Iteration   3: 3.640 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.605 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.565, 3.605, 3.640), stdev = 0.038
  CI (99.9%): [2.916, 4.293] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.003 ms/op
Iteration   1: 3.432 ±(99.9%) 0.003 ms/op
Iteration   2: 3.395 ±(99.9%) 0.003 ms/op
Iteration   3: 3.392 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.406 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.392, 3.406, 3.432), stdev = 0.022
  CI (99.9%): [2.999, 3.813] (assumes normal distribution)


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
# Warmup Iteration   1: 5.065 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.003 ms/op
Iteration   1: 3.613 ±(99.9%) 0.002 ms/op
Iteration   2: 3.629 ±(99.9%) 0.004 ms/op
Iteration   3: 3.579 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.607 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (3.579, 3.607, 3.629), stdev = 0.025
  CI (99.9%): [3.142, 4.072] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.440 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.025 ms/op
Iteration   1: 4.776 ±(99.9%) 0.013 ms/op
Iteration   2: 4.703 ±(99.9%) 0.009 ms/op
Iteration   3: 4.764 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.748 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (4.703, 4.748, 4.776), stdev = 0.039
  CI (99.9%): [4.035, 5.460] (assumes normal distribution)


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.008 ms/op
Iteration   1: 3.612 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  7.974 ms/op
                 createUser·p0.9999: 14.713 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   2: 3.608 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  11.368 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.609 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  16.253 ms/op
                 createUser·p0.9999: 28.410 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265938
  mean =      3.610 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7373 
    [ 2.500,  5.000) = 254364 
    [ 5.000,  7.500) = 3731 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      9.570 ms/op
     p(99.9900) =     28.010 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.801 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.008 ms/op
Iteration   1: 3.414 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  7.329 ms/op
                 existUser·p0.9999: 22.041 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.474 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  9.590 ms/op
                 existUser·p0.9999: 16.688 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   3: 3.409 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  7.023 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279752
  mean =      3.432 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5992 
    [ 2.500,  5.000) = 272009 
    [ 5.000,  7.500) = 1505 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      7.340 ms/op
     p(99.9900) =     21.726 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.008 ms/op
Iteration   1: 3.661 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 12.739 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 3.620 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  10.217 ms/op
                 getUser·p0.9999: 15.539 ms/op
                 getUser·p1.00:   16.220 ms/op

Iteration   3: 3.622 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  7.563 ms/op
                 getUser·p0.9999: 19.911 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264302
  mean =      3.634 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7954 
    [ 2.500,  5.000) = 251044 
    [ 5.000,  7.500) = 4755 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     19.225 ms/op
     p(99.9990) =     20.515 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 5.787 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.013 ms/op
Iteration   1: 4.720 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  14.896 ms/op
                 listUser·p0.9999: 18.576 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 4.760 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  18.090 ms/op
                 listUser·p0.9999: 25.070 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 4.767 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 24.225 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202246
  mean =      4.749 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 403 
    [ 2.500,  5.000) = 155446 
    [ 5.000,  7.500) = 41957 
    [ 7.500, 10.000) = 3865 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     16.998 ms/op
     p(99.9900) =     24.434 ms/op
     p(99.9990) =     27.033 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.901 ± 1.094  ops/ms
ClientGrpc.existUser                       thrpt       3   9.418 ± 0.563  ops/ms
ClientGrpc.getUser                         thrpt       3   8.902 ± 1.825  ops/ms
ClientGrpc.listUser                        thrpt       3   6.711 ± 0.187  ops/ms
ClientGrpc.createUser                       avgt       3   3.605 ± 0.688   ms/op
ClientGrpc.existUser                        avgt       3   3.406 ± 0.407   ms/op
ClientGrpc.getUser                          avgt       3   3.607 ± 0.465   ms/op
ClientGrpc.listUser                         avgt       3   4.748 ± 0.713   ms/op
ClientGrpc.createUser                     sample  265938   3.610 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.940           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.570           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.010           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.606           ms/op
ClientGrpc.existUser                      sample  279752   3.432 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.664           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.883           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.340           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.726           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.249           ms/op
ClientGrpc.getUser                        sample  264302   3.634 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.831           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.225           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.561           ms/op
ClientGrpc.listUser                       sample  202246   4.749 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.034           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.998           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.434           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
