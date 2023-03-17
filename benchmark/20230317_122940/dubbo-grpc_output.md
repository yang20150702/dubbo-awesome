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
# Warmup Iteration   1: 3.548 ops/ms
# Warmup Iteration   2: 7.443 ops/ms
# Warmup Iteration   3: 8.361 ops/ms
Iteration   1: 8.869 ops/ms
Iteration   2: 8.966 ops/ms
Iteration   3: 8.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.918 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (8.869, 8.918, 8.966), stdev = 0.048
  CI (99.9%): [8.037, 9.798] (assumes normal distribution)


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
# Warmup Iteration   1: 5.956 ops/ms
# Warmup Iteration   2: 8.862 ops/ms
# Warmup Iteration   3: 9.363 ops/ms
Iteration   1: 9.484 ops/ms
Iteration   2: 9.033 ops/ms
Iteration   3: 9.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.222 ±(99.9%) 4.266 ops/ms [Average]
  (min, avg, max) = (9.033, 9.222, 9.484), stdev = 0.234
  CI (99.9%): [4.957, 13.488] (assumes normal distribution)


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
# Warmup Iteration   1: 5.547 ops/ms
# Warmup Iteration   2: 8.329 ops/ms
# Warmup Iteration   3: 8.836 ops/ms
Iteration   1: 8.878 ops/ms
Iteration   2: 9.018 ops/ms
Iteration   3: 8.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.916 ±(99.9%) 1.621 ops/ms [Average]
  (min, avg, max) = (8.853, 8.916, 9.018), stdev = 0.089
  CI (99.9%): [7.295, 10.537] (assumes normal distribution)


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
# Warmup Iteration   1: 5.145 ops/ms
# Warmup Iteration   2: 6.329 ops/ms
# Warmup Iteration   3: 6.817 ops/ms
Iteration   1: 6.931 ops/ms
Iteration   2: 7.004 ops/ms
Iteration   3: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.028 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (6.931, 7.028, 7.150), stdev = 0.111
  CI (99.9%): [4.995, 9.061] (assumes normal distribution)


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
# Warmup Iteration   1: 5.269 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.005 ms/op
Iteration   1: 3.567 ±(99.9%) 0.004 ms/op
Iteration   2: 3.585 ±(99.9%) 0.003 ms/op
Iteration   3: 3.632 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.595 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.567, 3.595, 3.632), stdev = 0.034
  CI (99.9%): [2.977, 4.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.009 ms/op
Iteration   1: 3.404 ±(99.9%) 0.003 ms/op
Iteration   2: 3.376 ±(99.9%) 0.003 ms/op
Iteration   3: 3.380 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.387 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.376, 3.387, 3.404), stdev = 0.015
  CI (99.9%): [3.112, 3.661] (assumes normal distribution)


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.003 ms/op
Iteration   1: 3.577 ±(99.9%) 0.004 ms/op
Iteration   2: 3.629 ±(99.9%) 0.003 ms/op
Iteration   3: 3.632 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.613 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.577, 3.613, 3.632), stdev = 0.031
  CI (99.9%): [3.044, 4.182] (assumes normal distribution)


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
# Warmup Iteration   1: 6.390 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.987 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.015 ms/op
Iteration   1: 4.672 ±(99.9%) 0.039 ms/op
Iteration   2: 4.674 ±(99.9%) 0.015 ms/op
Iteration   3: 4.638 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.661 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (4.638, 4.661, 4.674), stdev = 0.020
  CI (99.9%): [4.289, 5.034] (assumes normal distribution)


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
# Warmup Iteration   1: 5.094 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.009 ms/op
Iteration   1: 3.657 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  8.368 ms/op
                 createUser·p0.9999: 14.278 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 3.569 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  9.640 ms/op
                 createUser·p0.9999: 16.778 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.631 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  14.596 ms/op
                 createUser·p0.9999: 24.609 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265246
  mean =      3.619 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5249 
    [ 2.500,  5.000) = 254515 
    [ 5.000,  7.500) = 4752 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     24.264 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.009 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.418 ms/op
                 existUser·p0.9999: 19.585 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.329 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  11.222 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.413 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  8.525 ms/op
                 existUser·p0.9999: 27.087 ms/op
                 existUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282852
  mean =      3.391 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6936 
    [ 2.500,  5.000) = 272658 
    [ 5.000,  7.500) = 2656 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     10.294 ms/op
     p(99.9900) =     25.976 ms/op
     p(99.9990) =     27.471 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 5.170 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.009 ms/op
Iteration   1: 3.648 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  11.528 ms/op
                 getUser·p0.9999: 15.663 ms/op
                 getUser·p1.00:   16.220 ms/op

Iteration   2: 3.753 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  9.122 ms/op
                 getUser·p0.9999: 16.293 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   3: 3.670 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  8.713 ms/op
                 getUser·p0.9999: 32.276 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 260050
  mean =      3.690 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8723 
    [ 2.500,  5.000) = 243596 
    [ 5.000,  7.500) = 6908 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     32.598 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 6.512 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.032 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.016 ms/op
Iteration   1: 4.657 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.644 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  14.720 ms/op
                 listUser·p0.9999: 16.793 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   2: 4.481 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  16.624 ms/op
                 listUser·p0.9999: 26.182 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 4.621 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.150 ms/op
                 listUser·p0.999:  20.187 ms/op
                 listUser·p0.9999: 22.776 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209447
  mean =      4.585 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 415 
    [ 2.500,  5.000) = 171727 
    [ 5.000,  7.500) = 33142 
    [ 7.500, 10.000) = 3578 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     16.550 ms/op
     p(99.9900) =     25.790 ms/op
     p(99.9990) =     26.372 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.918 ± 0.880  ops/ms
ClientGrpc.existUser                       thrpt       3   9.222 ± 4.266  ops/ms
ClientGrpc.getUser                         thrpt       3   8.916 ± 1.621  ops/ms
ClientGrpc.listUser                        thrpt       3   7.028 ± 2.033  ops/ms
ClientGrpc.createUser                       avgt       3   3.595 ± 0.617   ms/op
ClientGrpc.existUser                        avgt       3   3.387 ± 0.274   ms/op
ClientGrpc.getUser                          avgt       3   3.613 ± 0.569   ms/op
ClientGrpc.listUser                         avgt       3   4.661 ± 0.373   ms/op
ClientGrpc.createUser                     sample  265246   3.619 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.575           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.264           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.871           ms/op
ClientGrpc.existUser                      sample  282852   3.391 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.294           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.976           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.623           ms/op
ClientGrpc.getUser                        sample  260050   3.690 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.837           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.956           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.110           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.392           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.670           ms/op
ClientGrpc.listUser                       sample  209447   4.585 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.873           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.399           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.550           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.790           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
