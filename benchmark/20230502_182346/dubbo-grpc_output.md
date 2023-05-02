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
# Warmup Iteration   1: 4.092 ops/ms
# Warmup Iteration   2: 9.226 ops/ms
# Warmup Iteration   3: 10.343 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.686 ±(99.9%) 0.196 ops/ms [Average]
  (min, avg, max) = (10.676, 10.686, 10.697), stdev = 0.011
  CI (99.9%): [10.490, 10.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.373 ops/ms
# Warmup Iteration   2: 10.349 ops/ms
# Warmup Iteration   3: 11.098 ops/ms
Iteration   1: 11.135 ops/ms
Iteration   2: 11.010 ops/ms
Iteration   3: 11.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.089 ±(99.9%) 1.248 ops/ms [Average]
  (min, avg, max) = (11.010, 11.089, 11.135), stdev = 0.068
  CI (99.9%): [9.841, 12.336] (assumes normal distribution)


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
# Warmup Iteration   1: 7.193 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.286 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.391 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (10.286, 10.391, 10.582), stdev = 0.166
  CI (99.9%): [7.361, 13.420] (assumes normal distribution)


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
# Warmup Iteration   1: 5.428 ops/ms
# Warmup Iteration   2: 7.675 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.087 ops/ms
Iteration   2: 8.106 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.080 ±(99.9%) 0.558 ops/ms [Average]
  (min, avg, max) = (8.047, 8.080, 8.106), stdev = 0.031
  CI (99.9%): [7.523, 8.638] (assumes normal distribution)


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.000, 3.027, 3.055), stdev = 0.028
  CI (99.9%): [2.520, 3.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.003 ms/op
Iteration   1: 2.851 ±(99.9%) 0.003 ms/op
Iteration   2: 2.884 ±(99.9%) 0.003 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (2.851, 2.910, 2.995), stdev = 0.075
  CI (99.9%): [1.537, 4.283] (assumes normal distribution)


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
# Warmup Iteration   1: 4.232 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.006, 3.025, 3.040), stdev = 0.017
  CI (99.9%): [2.716, 3.334] (assumes normal distribution)


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
# Warmup Iteration   1: 5.732 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.007 ms/op
Iteration   1: 3.944 ±(99.9%) 0.027 ms/op
Iteration   2: 3.889 ±(99.9%) 0.028 ms/op
Iteration   3: 3.921 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.889, 3.918, 3.944), stdev = 0.027
  CI (99.9%): [3.420, 4.416] (assumes normal distribution)


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.006 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  11.489 ms/op
                 createUser·p0.9999: 14.023 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.719 ms/op
                 createUser·p0.9999: 14.155 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.004 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315594
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 879 
    [ 1.250,  2.500) = 20812 
    [ 2.500,  3.750) = 279027 
    [ 3.750,  5.000) = 13459 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 121 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     16.431 ms/op
     p(99.9990) =     16.805 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.005 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.081 ms/op
                 existUser·p0.9999: 12.690 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.700 ms/op
                 existUser·p0.9999: 14.001 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 18.879 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325815
  mean =      2.946 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 998 
    [ 1.250,  2.500) = 30898 
    [ 2.500,  3.750) = 281486 
    [ 3.750,  5.000) = 11229 
    [ 5.000,  6.250) = 513 
    [ 6.250,  7.500) = 361 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.538 ms/op
     p(99.9900) =     16.032 ms/op
     p(99.9990) =     19.218 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.724 ms/op
                 getUser·p0.9999: 13.084 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.364 ms/op
                 getUser·p0.9999: 18.529 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.244 ms/op
                 getUser·p0.9999: 16.080 ms/op
                 getUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315079
  mean =      3.048 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 362 
    [ 1.250,  2.500) = 17800 
    [ 2.500,  3.750) = 281077 
    [ 3.750,  5.000) = 14316 
    [ 5.000,  6.250) = 958 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.420 ms/op
     p(99.9900) =     18.021 ms/op
     p(99.9990) =     18.837 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 5.845 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.012 ms/op
Iteration   1: 3.949 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.466 ms/op
                 listUser·p0.9999: 21.063 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 3.943 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.662 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.791 ms/op
                 listUser·p0.9999: 16.036 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.948 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  17.235 ms/op
                 listUser·p0.9999: 27.158 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243283
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2260 
    [ 2.500,  5.000) = 221574 
    [ 5.000,  7.500) = 18374 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.195 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.464 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.686 ± 0.196  ops/ms
ClientGrpc.existUser                       thrpt       3  11.089 ± 1.248  ops/ms
ClientGrpc.getUser                         thrpt       3  10.391 ± 3.030  ops/ms
ClientGrpc.listUser                        thrpt       3   8.080 ± 0.558  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.507   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 1.373   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.309   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.498   ms/op
ClientGrpc.createUser                     sample  315594   3.041 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.423           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.274           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.431           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.810           ms/op
ClientGrpc.existUser                      sample  325815   2.946 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.538           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.032           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.300           ms/op
ClientGrpc.getUser                        sample  315079   3.048 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.802           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.420           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.021           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.973           ms/op
ClientGrpc.listUser                       sample  243283   3.947 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.974           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.195           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.526           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
