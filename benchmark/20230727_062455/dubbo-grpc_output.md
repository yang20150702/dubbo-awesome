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
# Warmup Iteration   1: 3.391 ops/ms
# Warmup Iteration   2: 6.060 ops/ms
# Warmup Iteration   3: 7.215 ops/ms
Iteration   1: 7.438 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.643 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (7.438, 7.643, 7.780), stdev = 0.181
  CI (99.9%): [4.345, 10.940] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.631 ops/ms
# Warmup Iteration   2: 7.338 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.403 ops/ms
Iteration   2: 8.715 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.577 ±(99.9%) 2.910 ops/ms [Average]
  (min, avg, max) = (8.403, 8.577, 8.715), stdev = 0.159
  CI (99.9%): [5.668, 11.487] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ops/ms
# Warmup Iteration   2: 7.550 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 8.210 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 8.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.212 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (8.153, 8.212, 8.274), stdev = 0.061
  CI (99.9%): [7.105, 9.319] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ops/ms
# Warmup Iteration   2: 5.640 ops/ms
# Warmup Iteration   3: 5.990 ops/ms
Iteration   1: 6.193 ops/ms
Iteration   2: 5.954 ops/ms
Iteration   3: 6.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.126 ±(99.9%) 2.738 ops/ms [Average]
  (min, avg, max) = (5.954, 6.126, 6.230), stdev = 0.150
  CI (99.9%): [3.387, 8.864] (assumes normal distribution)


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
# Warmup Iteration   1: 5.857 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.010 ms/op
Iteration   1: 3.950 ±(99.9%) 0.004 ms/op
Iteration   2: 3.871 ±(99.9%) 0.004 ms/op
Iteration   3: 3.915 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.912 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (3.871, 3.912, 3.950), stdev = 0.040
  CI (99.9%): [3.187, 4.636] (assumes normal distribution)


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
# Warmup Iteration   1: 5.391 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.004 ms/op
Iteration   1: 3.734 ±(99.9%) 0.003 ms/op
Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
Iteration   3: 3.800 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.745 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.701, 3.745, 3.800), stdev = 0.051
  CI (99.9%): [2.819, 4.671] (assumes normal distribution)


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
# Warmup Iteration   1: 5.702 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.005 ms/op
Iteration   1: 3.922 ±(99.9%) 0.005 ms/op
Iteration   2: 3.779 ±(99.9%) 0.005 ms/op
Iteration   3: 3.818 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.840 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (3.779, 3.840, 3.922), stdev = 0.074
  CI (99.9%): [2.498, 5.181] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.914 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.474 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.998 ±(99.9%) 0.015 ms/op
Iteration   1: 4.901 ±(99.9%) 0.014 ms/op
Iteration   2: 4.950 ±(99.9%) 0.014 ms/op
Iteration   3: 4.771 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.874 ±(99.9%) 1.690 ms/op [Average]
  (min, avg, max) = (4.771, 4.874, 4.950), stdev = 0.093
  CI (99.9%): [3.184, 6.564] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.715 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.009 ms/op
Iteration   1: 3.632 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  16.432 ms/op
                 createUser·p0.9999: 22.223 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.591 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  10.204 ms/op
                 createUser·p0.9999: 20.450 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   3: 3.620 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  9.267 ms/op
                 createUser·p0.9999: 24.712 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265521
  mean =      3.614 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4296 
    [ 2.500,  5.000) = 256807 
    [ 5.000,  7.500) = 3724 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     10.132 ms/op
     p(99.9900) =     24.460 ms/op
     p(99.9990) =     25.016 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 4.914 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.009 ms/op
Iteration   1: 3.439 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.012 ms/op
                 existUser·p0.9999: 14.855 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 3.443 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  8.382 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   3: 3.538 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.924 ms/op
                 existUser·p0.999:  11.522 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276218
  mean =      3.473 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5806 
    [ 2.500,  5.000) = 265766 
    [ 5.000,  7.500) = 4040 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      8.877 ms/op
     p(99.9900) =     20.525 ms/op
     p(99.9990) =     22.454 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 5.829 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.009 ms/op
Iteration   1: 3.604 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  12.196 ms/op
                 getUser·p0.9999: 25.170 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.574 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.531 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  11.274 ms/op
                 getUser·p0.9999: 15.845 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   3: 3.651 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  9.674 ms/op
                 getUser·p0.9999: 33.718 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265721
  mean =      3.610 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8374 
    [ 2.500,  5.000) = 251147 
    [ 5.000,  7.500) = 5337 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     10.589 ms/op
     p(99.9900) =     33.077 ms/op
     p(99.9990) =     35.609 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 6.013 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.909 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.254 ±(99.9%) 0.019 ms/op
Iteration   1: 5.433 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 27.074 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 5.114 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   9.453 ms/op
                 listUser·p0.999:  20.611 ms/op
                 listUser·p0.9999: 30.368 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 4.902 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  20.469 ms/op
                 listUser·p0.9999: 30.522 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186709
  mean =      5.141 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 501 
    [ 2.500,  5.000) = 110210 
    [ 5.000,  7.500) = 63773 
    [ 7.500, 10.000) = 10445 
    [10.000, 12.500) = 1280 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     19.769 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     32.032 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.643 ± 3.297  ops/ms
ClientGrpc.existUser                       thrpt       3   8.577 ± 2.910  ops/ms
ClientGrpc.getUser                         thrpt       3   8.212 ± 1.107  ops/ms
ClientGrpc.listUser                        thrpt       3   6.126 ± 2.738  ops/ms
ClientGrpc.createUser                       avgt       3   3.912 ± 0.724   ms/op
ClientGrpc.existUser                        avgt       3   3.745 ± 0.926   ms/op
ClientGrpc.getUser                          avgt       3   3.840 ± 1.342   ms/op
ClientGrpc.listUser                         avgt       3   4.874 ± 1.690   ms/op
ClientGrpc.createUser                     sample  265521   3.614 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.822           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.132           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.460           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.362           ms/op
ClientGrpc.existUser                      sample  276218   3.473 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.648           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.985           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.525           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  265721   3.610 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.799           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.589           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.077           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.652           ms/op
ClientGrpc.listUser                       sample  186709   5.141 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.856           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.769           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.343           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.145           ms/op
