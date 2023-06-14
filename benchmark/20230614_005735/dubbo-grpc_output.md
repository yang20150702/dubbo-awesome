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
# Warmup Iteration   1: 4.209 ops/ms
# Warmup Iteration   2: 9.297 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.654 ±(99.9%) 1.133 ops/ms [Average]
  (min, avg, max) = (10.602, 10.654, 10.723), stdev = 0.062
  CI (99.9%): [9.521, 11.786] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.762 ops/ms
# Warmup Iteration   2: 10.848 ops/ms
# Warmup Iteration   3: 10.946 ops/ms
Iteration   1: 11.015 ops/ms
Iteration   2: 11.087 ops/ms
Iteration   3: 11.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.057 ±(99.9%) 0.684 ops/ms [Average]
  (min, avg, max) = (11.015, 11.057, 11.087), stdev = 0.038
  CI (99.9%): [10.372, 11.741] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.242 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.592 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (10.492, 10.592, 10.760), stdev = 0.146
  CI (99.9%): [7.922, 13.262] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ops/ms
# Warmup Iteration   2: 8.076 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 8.230 ops/ms
Iteration   2: 8.404 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.237 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (8.077, 8.237, 8.404), stdev = 0.164
  CI (99.9%): [5.251, 11.223] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.130 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.032, 3.042, 3.053), stdev = 0.010
  CI (99.9%): [2.853, 3.231] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.003 ms/op
Iteration   1: 2.862 ±(99.9%) 0.003 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.916 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.862, 2.891, 2.916), stdev = 0.027
  CI (99.9%): [2.391, 3.392] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.008, 3.042, 3.076), stdev = 0.034
  CI (99.9%): [2.420, 3.663] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.412 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.016 ms/op
Iteration   1: 3.928 ±(99.9%) 0.053 ms/op
Iteration   2: 3.936 ±(99.9%) 0.008 ms/op
Iteration   3: 3.859 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.908 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.859, 3.908, 3.936), stdev = 0.042
  CI (99.9%): [3.139, 4.677] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  12.396 ms/op
                 createUser·p0.9999: 27.719 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.742 ms/op
                 createUser·p0.9999: 24.042 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.615 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317948
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23269 
    [ 2.500,  5.000) = 293261 
    [ 5.000,  7.500) = 1058 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     24.131 ms/op
     p(99.9990) =     27.912 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.005 ms/op
Iteration   1: 2.878 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.356 ms/op
                 existUser·p0.999:  7.918 ms/op
                 existUser·p0.9999: 19.133 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 2.897 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   3.948 ms/op
                 existUser·p0.999:  6.108 ms/op
                 existUser·p0.9999: 14.384 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.478 ms/op
                 existUser·p0.9999: 18.057 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331348
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1857 
    [ 1.250,  2.500) = 41045 
    [ 2.500,  3.750) = 278386 
    [ 3.750,  5.000) = 9149 
    [ 5.000,  6.250) = 409 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.018 ms/op
     p(99.9900) =     18.505 ms/op
     p(99.9990) =     19.487 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.357 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.564 ms/op
                 getUser·p0.9999: 19.315 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  6.913 ms/op
                 getUser·p0.9999: 22.469 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.602 ms/op
                 getUser·p0.9999: 21.379 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317771
  mean =      3.019 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21506 
    [ 2.500,  5.000) = 294839 
    [ 5.000,  7.500) = 1230 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.705 ms/op
     p(99.9900) =     21.798 ms/op
     p(99.9990) =     22.670 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.553 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.011 ms/op
Iteration   1: 3.905 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 18.114 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.597 ms/op
                 listUser·p0.9999: 23.128 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  21.253 ms/op
                 listUser·p0.9999: 26.051 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243762
  mean =      3.938 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2652 
    [ 2.500,  5.000) = 221755 
    [ 5.000,  7.500) = 18122 
    [ 7.500, 10.000) = 828 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     16.064 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     26.382 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.654 ± 1.133  ops/ms
ClientGrpc.existUser                       thrpt       3  11.057 ± 0.684  ops/ms
ClientGrpc.getUser                         thrpt       3  10.592 ± 2.670  ops/ms
ClientGrpc.listUser                        thrpt       3   8.237 ± 2.986  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.189   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.500   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.622   ms/op
ClientGrpc.listUser                         avgt       3   3.908 ± 0.769   ms/op
ClientGrpc.createUser                     sample  317948   3.020 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.878           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.131           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.984           ms/op
ClientGrpc.existUser                      sample  331348   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.699           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.018           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.505           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.562           ms/op
ClientGrpc.getUser                        sample  317771   3.019 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.705           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.798           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  243762   3.938 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.135           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.064           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.690           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
