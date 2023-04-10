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
# Warmup Iteration   1: 3.612 ops/ms
# Warmup Iteration   2: 7.401 ops/ms
# Warmup Iteration   3: 8.657 ops/ms
Iteration   1: 9.076 ops/ms
Iteration   2: 8.227 ops/ms
Iteration   3: 8.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.716 ±(99.9%) 8.006 ops/ms [Average]
  (min, avg, max) = (8.227, 8.716, 9.076), stdev = 0.439
  CI (99.9%): [0.709, 16.722] (assumes normal distribution)


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
# Warmup Iteration   1: 5.933 ops/ms
# Warmup Iteration   2: 8.746 ops/ms
# Warmup Iteration   3: 9.304 ops/ms
Iteration   1: 9.109 ops/ms
Iteration   2: 8.661 ops/ms
Iteration   3: 9.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.019 ±(99.9%) 5.877 ops/ms [Average]
  (min, avg, max) = (8.661, 9.019, 9.286), stdev = 0.322
  CI (99.9%): [3.142, 14.895] (assumes normal distribution)


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
# Warmup Iteration   1: 5.868 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.142 ops/ms
Iteration   2: 9.353 ops/ms
Iteration   3: 9.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.230 ±(99.9%) 1.996 ops/ms [Average]
  (min, avg, max) = (9.142, 9.230, 9.353), stdev = 0.109
  CI (99.9%): [7.234, 11.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.849 ops/ms
# Warmup Iteration   2: 6.945 ops/ms
# Warmup Iteration   3: 6.966 ops/ms
Iteration   1: 7.184 ops/ms
Iteration   2: 6.999 ops/ms
Iteration   3: 7.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.099 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (6.999, 7.099, 7.184), stdev = 0.093
  CI (99.9%): [5.398, 8.799] (assumes normal distribution)


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
# Warmup Iteration   1: 4.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.005 ms/op
Iteration   1: 3.339 ±(99.9%) 0.005 ms/op
Iteration   2: 3.406 ±(99.9%) 0.005 ms/op
Iteration   3: 3.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.403 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.339, 3.403, 3.465), stdev = 0.063
  CI (99.9%): [2.251, 4.555] (assumes normal distribution)


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.004 ms/op
Iteration   1: 3.373 ±(99.9%) 0.004 ms/op
Iteration   2: 3.362 ±(99.9%) 0.004 ms/op
Iteration   3: 3.302 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.346 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.302, 3.346, 3.373), stdev = 0.038
  CI (99.9%): [2.645, 4.046] (assumes normal distribution)


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.003 ms/op
Iteration   1: 3.420 ±(99.9%) 0.003 ms/op
Iteration   2: 3.451 ±(99.9%) 0.003 ms/op
Iteration   3: 3.480 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.450 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.420, 3.450, 3.480), stdev = 0.030
  CI (99.9%): [2.897, 4.004] (assumes normal distribution)


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
# Warmup Iteration   1: 5.967 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.938 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.008 ms/op
Iteration   1: 4.441 ±(99.9%) 0.009 ms/op
Iteration   2: 4.474 ±(99.9%) 0.025 ms/op
Iteration   3: 4.441 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.452 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (4.441, 4.452, 4.474), stdev = 0.019
  CI (99.9%): [4.109, 4.794] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.102 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.010 ms/op
Iteration   1: 3.719 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  11.501 ms/op
                 createUser·p0.9999: 15.696 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   2: 3.423 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  8.841 ms/op
                 createUser·p0.9999: 16.148 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   3: 3.419 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  10.666 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 273164
  mean =      3.515 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 310 
    [ 1.250,  2.500) = 9315 
    [ 2.500,  3.750) = 189588 
    [ 3.750,  5.000) = 68419 
    [ 5.000,  6.250) = 4384 
    [ 6.250,  7.500) = 622 
    [ 7.500,  8.750) = 158 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     10.352 ms/op
     p(99.9900) =     18.690 ms/op
     p(99.9990) =     19.678 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.007 ms/op
Iteration   1: 3.243 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.006 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 15.289 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 3.315 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  7.082 ms/op
                 existUser·p0.9999: 18.633 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 32.153 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 292861
  mean =      3.277 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19782 
    [ 2.500,  5.000) = 270142 
    [ 5.000,  7.500) = 2543 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      8.573 ms/op
     p(99.9900) =     31.120 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.009 ms/op
Iteration   1: 3.515 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  11.450 ms/op
                 getUser·p0.9999: 16.640 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 3.498 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  9.304 ms/op
                 getUser·p0.9999: 15.723 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   3: 3.475 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 274751
  mean =      3.496 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7871 
    [ 2.500,  5.000) = 262076 
    [ 5.000,  7.500) = 4276 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.457 ms/op
     p(99.9900) =     19.630 ms/op
     p(99.9990) =     20.603 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.924 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.089 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.574 ±(99.9%) 0.014 ms/op
Iteration   1: 4.523 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  13.948 ms/op
                 listUser·p0.9999: 19.949 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.599 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 21.760 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 4.699 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  18.774 ms/op
                 listUser·p0.9999: 23.213 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208362
  mean =      4.606 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 432 
    [ 2.500,  5.000) = 169917 
    [ 5.000,  7.500) = 34021 
    [ 7.500, 10.000) = 3429 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     16.798 ms/op
     p(99.9900) =     21.703 ms/op
     p(99.9990) =     23.942 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.716 ± 8.006  ops/ms
ClientGrpc.existUser                       thrpt       3   9.019 ± 5.877  ops/ms
ClientGrpc.getUser                         thrpt       3   9.230 ± 1.996  ops/ms
ClientGrpc.listUser                        thrpt       3   7.099 ± 1.700  ops/ms
ClientGrpc.createUser                       avgt       3   3.403 ± 1.152   ms/op
ClientGrpc.existUser                        avgt       3   3.346 ± 0.701   ms/op
ClientGrpc.getUser                          avgt       3   3.450 ± 0.554   ms/op
ClientGrpc.listUser                         avgt       3   4.452 ± 0.343   ms/op
ClientGrpc.createUser                     sample  273164   3.515 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.480           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.352           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.690           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  292861   3.277 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.005           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.573           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.120           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.522           ms/op
ClientGrpc.getUser                        sample  274751   3.496 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.841           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.018           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.457           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.630           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  208362   4.606 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.006           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.432           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.200           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.798           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.703           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
