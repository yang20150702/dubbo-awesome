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
# Warmup Iteration   1: 3.880 ops/ms
# Warmup Iteration   2: 8.512 ops/ms
# Warmup Iteration   3: 9.808 ops/ms
Iteration   1: 10.011 ops/ms
Iteration   2: 9.980 ops/ms
Iteration   3: 10.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.027 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (9.980, 10.027, 10.091), stdev = 0.057
  CI (99.9%): [8.986, 11.069] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.873 ops/ms
# Warmup Iteration   2: 9.892 ops/ms
# Warmup Iteration   3: 10.377 ops/ms
Iteration   1: 10.556 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.541 ±(99.9%) 0.641 ops/ms [Average]
  (min, avg, max) = (10.500, 10.541, 10.566), stdev = 0.035
  CI (99.9%): [9.899, 11.182] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 9.905 ops/ms
Iteration   1: 10.238 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.211 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (10.167, 10.211, 10.238), stdev = 0.039
  CI (99.9%): [9.505, 10.917] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.964 ops/ms
# Warmup Iteration   2: 7.643 ops/ms
# Warmup Iteration   3: 7.940 ops/ms
Iteration   1: 8.065 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.107 ±(99.9%) 0.736 ops/ms [Average]
  (min, avg, max) = (8.065, 8.107, 8.145), stdev = 0.040
  CI (99.9%): [7.371, 8.843] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.603 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.004 ms/op
Iteration   1: 3.200 ±(99.9%) 0.009 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.190 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.146, 3.179, 3.200), stdev = 0.029
  CI (99.9%): [2.658, 3.700] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.002 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
Iteration   2: 2.945 ±(99.9%) 0.004 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.966 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.945, 2.966, 2.988), stdev = 0.021
  CI (99.9%): [2.575, 3.358] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.664 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.003 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
Iteration   3: 3.160 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.182 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.160, 3.182, 3.209), stdev = 0.025
  CI (99.9%): [2.730, 3.634] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.828 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.013 ms/op
Iteration   1: 3.803 ±(99.9%) 0.009 ms/op
Iteration   2: 3.915 ±(99.9%) 0.009 ms/op
Iteration   3: 3.959 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 1.472 ms/op [Average]
  (min, avg, max) = (3.803, 3.892, 3.959), stdev = 0.081
  CI (99.9%): [2.421, 5.364] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.687 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
Iteration   1: 3.170 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  12.633 ms/op
                 createUser·p0.9999: 25.625 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  10.938 ms/op
                 createUser·p0.9999: 22.353 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.203 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.706 ms/op
                 createUser·p0.999:  13.146 ms/op
                 createUser·p0.9999: 27.655 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299515
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6771 
    [ 2.500,  5.000) = 290619 
    [ 5.000,  7.500) = 1544 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     12.089 ms/op
     p(99.9900) =     25.561 ms/op
     p(99.9990) =     30.705 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.295 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  8.885 ms/op
                 existUser·p0.9999: 14.859 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 15.392 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  9.147 ms/op
                 existUser·p0.9999: 20.328 ms/op
                 existUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316909
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23650 
    [ 2.500,  5.000) = 291408 
    [ 5.000,  7.500) = 1413 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     17.475 ms/op
     p(99.9990) =     20.704 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
Iteration   1: 3.198 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  9.059 ms/op
                 getUser·p0.9999: 23.162 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  9.012 ms/op
                 getUser·p0.9999: 19.736 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  13.645 ms/op
                 getUser·p0.9999: 21.053 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306337
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9271 
    [ 2.500,  5.000) = 294930 
    [ 5.000,  7.500) = 1617 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     22.327 ms/op
     p(99.9990) =     30.241 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 6.440 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.010 ms/op
Iteration   1: 4.011 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.654 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 37.620 ms/op
                 listUser·p1.00:   38.732 ms/op

Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 24.743 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.419 ms/op
                 listUser·p0.9999: 19.989 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239470
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2232 
    [ 2.500,  5.000) = 219121 
    [ 5.000,  7.500) = 16087 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     38.459 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.027 ± 1.042  ops/ms
ClientGrpc.existUser                       thrpt       3  10.541 ± 0.641  ops/ms
ClientGrpc.getUser                         thrpt       3  10.211 ± 0.706  ops/ms
ClientGrpc.listUser                        thrpt       3   8.107 ± 0.736  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 0.521   ms/op
ClientGrpc.existUser                        avgt       3   2.966 ± 0.392   ms/op
ClientGrpc.getUser                          avgt       3   3.182 ± 0.452   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 1.472   ms/op
ClientGrpc.createUser                     sample  299515   3.207 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.710           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.002           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.089           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.561           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.293           ms/op
ClientGrpc.existUser                      sample  316909   3.030 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.599           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.315           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.475           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  306337   3.136 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.646           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.421           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.327           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.506           ms/op
ClientGrpc.listUser                       sample  239470   4.006 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.654           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.417           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.865           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.732           ms/op
