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
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 9.219 ops/ms
# Warmup Iteration   3: 10.325 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.421 ±(99.9%) 4.430 ops/ms [Average]
  (min, avg, max) = (10.141, 10.421, 10.568), stdev = 0.243
  CI (99.9%): [5.991, 14.851] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 9.448 ops/ms
# Warmup Iteration   2: 10.482 ops/ms
# Warmup Iteration   3: 11.137 ops/ms
Iteration   1: 10.987 ops/ms
Iteration   2: 10.807 ops/ms
Iteration   3: 11.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.986 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (10.807, 10.986, 11.164), stdev = 0.178
  CI (99.9%): [7.730, 14.243] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.506 ops/ms
# Warmup Iteration   2: 10.223 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 11.003 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.596 ±(99.9%) 6.440 ops/ms [Average]
  (min, avg, max) = (10.369, 10.596, 11.003), stdev = 0.353
  CI (99.9%): [4.157, 17.036] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.119 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 7.578 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 7.665 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.845 ±(99.9%) 2.889 ops/ms [Average]
  (min, avg, max) = (7.665, 7.845, 7.965), stdev = 0.158
  CI (99.9%): [4.956, 10.734] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.195 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.004 ms/op
Iteration   1: 3.225 ±(99.9%) 0.002 ms/op
Iteration   2: 3.130 ±(99.9%) 0.003 ms/op
Iteration   3: 3.264 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.206 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (3.130, 3.206, 3.264), stdev = 0.069
  CI (99.9%): [1.952, 4.461] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.001 ms/op
Iteration   3: 3.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.106 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.077, 3.106, 3.126), stdev = 0.025
  CI (99.9%): [2.645, 3.567] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.002 ms/op
Iteration   1: 3.207 ±(99.9%) 0.002 ms/op
Iteration   2: 3.262 ±(99.9%) 0.002 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.213 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.170, 3.213, 3.262), stdev = 0.046
  CI (99.9%): [2.373, 4.052] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.531 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.410 ±(99.9%) 0.015 ms/op
Iteration   1: 4.286 ±(99.9%) 0.018 ms/op
Iteration   2: 3.870 ±(99.9%) 0.004 ms/op
Iteration   3: 3.862 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.006 ±(99.9%) 4.423 ms/op [Average]
  (min, avg, max) = (3.862, 4.006, 4.286), stdev = 0.242
  CI (99.9%): [≈ 0, 8.429] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.716 ms/op
                 createUser·p0.9999: 12.307 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.499 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.641 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.645 ms/op
                 createUser·p0.9999: 15.570 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312927
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24726 
    [ 2.500,  5.000) = 287435 
    [ 5.000,  7.500) = 461 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.399 ms/op
     p(99.9900) =     19.979 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
Iteration   1: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.471 ms/op
                 existUser·p0.9999: 11.485 ms/op
                 existUser·p1.00:   11.616 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.456 ms/op
                 existUser·p0.9999: 12.765 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 14.574 ms/op
                 existUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330942
  mean =      2.899 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3311 
    [ 1.250,  2.500) = 54073 
    [ 2.500,  3.750) = 259038 
    [ 3.750,  5.000) = 13487 
    [ 5.000,  6.250) = 522 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.194 ms/op
     p(99.9900) =     13.269 ms/op
     p(99.9990) =     14.675 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.843 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 16.276 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.719 ms/op
                 getUser·p0.9999: 13.198 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.417 ms/op
                 getUser·p0.9999: 15.677 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318282
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2679 
    [ 1.250,  2.500) = 27935 
    [ 2.500,  3.750) = 269543 
    [ 3.750,  5.000) = 17236 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.720 ms/op
     p(99.9900) =     15.794 ms/op
     p(99.9990) =     18.660 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.944 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
Iteration   1: 4.113 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.161 ms/op
                 listUser·p0.9999: 14.495 ms/op
                 listUser·p1.00:   14.778 ms/op

Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.608 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.957 ms/op
                 listUser·p0.999:  15.822 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.157 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.206 ms/op
                 listUser·p0.9999: 17.562 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237956
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4658 
    [ 2.500,  5.000) = 200125 
    [ 5.000,  7.500) = 31905 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.091 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     24.965 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.421 ± 4.430  ops/ms
ClientGrpc.existUser                       thrpt       3  10.986 ± 3.256  ops/ms
ClientGrpc.getUser                         thrpt       3  10.596 ± 6.440  ops/ms
ClientGrpc.listUser                        thrpt       3   7.845 ± 2.889  ops/ms
ClientGrpc.createUser                       avgt       3   3.206 ± 1.254   ms/op
ClientGrpc.existUser                        avgt       3   3.106 ± 0.461   ms/op
ClientGrpc.getUser                          avgt       3   3.213 ± 0.839   ms/op
ClientGrpc.listUser                         avgt       3   4.006 ± 4.423   ms/op
ClientGrpc.createUser                     sample  312927   3.066 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.499           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.399           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.979           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.578           ms/op
ClientGrpc.existUser                      sample  330942   2.899 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.643           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.194           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.269           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.729           ms/op
ClientGrpc.getUser                        sample  318282   3.014 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.539           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.720           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.794           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.809           ms/op
ClientGrpc.listUser                       sample  237956   4.034 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.608           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.091           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.890           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.461           ms/op
