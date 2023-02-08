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
# Warmup Iteration   1: 3.943 ops/ms
# Warmup Iteration   2: 8.594 ops/ms
# Warmup Iteration   3: 9.651 ops/ms
Iteration   1: 9.818 ops/ms
Iteration   2: 9.822 ops/ms
Iteration   3: 9.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.812 ±(99.9%) 0.255 ops/ms [Average]
  (min, avg, max) = (9.796, 9.812, 9.822), stdev = 0.014
  CI (99.9%): [9.557, 10.068] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.336 ops/ms
# Warmup Iteration   2: 9.966 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.242 ops/ms
Iteration   2: 10.337 ops/ms
Iteration   3: 10.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.256 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (10.190, 10.256, 10.337), stdev = 0.074
  CI (99.9%): [8.898, 11.615] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.259 ops/ms
# Warmup Iteration   2: 9.362 ops/ms
# Warmup Iteration   3: 9.254 ops/ms
Iteration   1: 9.527 ops/ms
Iteration   2: 9.970 ops/ms
Iteration   3: 9.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.829 ±(99.9%) 4.770 ops/ms [Average]
  (min, avg, max) = (9.527, 9.829, 9.989), stdev = 0.261
  CI (99.9%): [5.058, 14.599] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ops/ms
# Warmup Iteration   2: 7.459 ops/ms
# Warmup Iteration   3: 7.573 ops/ms
Iteration   1: 7.637 ops/ms
Iteration   2: 7.611 ops/ms
Iteration   3: 7.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.639 ±(99.9%) 0.530 ops/ms [Average]
  (min, avg, max) = (7.611, 7.639, 7.669), stdev = 0.029
  CI (99.9%): [7.109, 8.169] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.013 ms/op
Iteration   1: 3.263 ±(99.9%) 0.002 ms/op
Iteration   2: 3.273 ±(99.9%) 0.003 ms/op
Iteration   3: 3.219 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.252 ±(99.9%) 0.532 ms/op [Average]
  (min, avg, max) = (3.219, 3.252, 3.273), stdev = 0.029
  CI (99.9%): [2.720, 3.784] (assumes normal distribution)


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 2.908 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.016 ms/op
Iteration   3: 3.097 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.029 ±(99.9%) 1.922 ms/op [Average]
  (min, avg, max) = (2.908, 3.029, 3.097), stdev = 0.105
  CI (99.9%): [1.108, 4.951] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.003 ms/op
Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
Iteration   3: 3.174 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.192 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.172, 3.192, 3.229), stdev = 0.032
  CI (99.9%): [2.606, 3.777] (assumes normal distribution)


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
# Warmup Iteration   1: 5.613 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.032 ms/op
Iteration   1: 4.167 ±(99.9%) 0.008 ms/op
Iteration   2: 4.165 ±(99.9%) 0.029 ms/op
Iteration   3: 4.214 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.182 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (4.165, 4.182, 4.214), stdev = 0.028
  CI (99.9%): [3.672, 4.692] (assumes normal distribution)


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.483 ms/op
                 createUser·p0.9999: 13.064 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.444 ms/op
                 createUser·p0.9999: 15.532 ms/op
                 createUser·p1.00:   16.073 ms/op

Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.849 ms/op
                 createUser·p0.9999: 16.974 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302948
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 542 
    [ 1.250,  2.500) = 26393 
    [ 2.500,  3.750) = 232512 
    [ 3.750,  5.000) = 42407 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 69 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.570 ms/op
     p(99.9900) =     16.351 ms/op
     p(99.9990) =     17.267 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  5.951 ms/op
                 existUser·p0.9999: 12.414 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.676 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.531 ms/op
                 existUser·p0.9999: 27.540 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315581
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35885 
    [ 2.500,  5.000) = 278689 
    [ 5.000,  7.500) = 798 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.327 ms/op
     p(99.9000) =      6.434 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.744 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  8.258 ms/op
                 getUser·p0.9999: 16.401 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 3.326 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  10.193 ms/op
                 getUser·p0.9999: 13.660 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 3.209 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.709 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295878
  mean =      3.245 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 433 
    [ 1.250,  2.500) = 17859 
    [ 2.500,  3.750) = 224221 
    [ 3.750,  5.000) = 52095 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 312 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.947 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     18.057 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
Iteration   1: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.035 ms/op
                 listUser·p0.9999: 21.599 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 4.207 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  17.888 ms/op
                 listUser·p0.9999: 23.088 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 4.119 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  17.120 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232257
  mean =      4.137 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1554 
    [ 2.500,  5.000) = 200897 
    [ 5.000,  7.500) = 28267 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     16.769 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     25.036 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.812 ± 0.255  ops/ms
ClientGrpc.existUser                       thrpt       3  10.256 ± 1.358  ops/ms
ClientGrpc.getUser                         thrpt       3   9.829 ± 4.770  ops/ms
ClientGrpc.listUser                        thrpt       3   7.639 ± 0.530  ops/ms
ClientGrpc.createUser                       avgt       3   3.252 ± 0.532   ms/op
ClientGrpc.existUser                        avgt       3   3.029 ± 1.922   ms/op
ClientGrpc.getUser                          avgt       3   3.192 ± 0.586   ms/op
ClientGrpc.listUser                         avgt       3   4.182 ± 0.510   ms/op
ClientGrpc.createUser                     sample  302948   3.170 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.733           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.570           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.351           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.695           ms/op
ClientGrpc.existUser                      sample  315581   3.042 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.327           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.434           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.820           ms/op
ClientGrpc.getUser                        sample  295878   3.245 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.718           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.211           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.947           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.302           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  232257   4.137 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.684           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.769           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.774           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.133           ms/op
