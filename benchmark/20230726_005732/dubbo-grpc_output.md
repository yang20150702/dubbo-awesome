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
# Warmup Iteration   1: 2.398 ops/ms
# Warmup Iteration   2: 5.932 ops/ms
# Warmup Iteration   3: 7.529 ops/ms
Iteration   1: 7.964 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.978 ±(99.9%) 0.503 ops/ms [Average]
  (min, avg, max) = (7.960, 7.978, 8.009), stdev = 0.028
  CI (99.9%): [7.475, 8.480] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.702 ops/ms
# Warmup Iteration   2: 7.901 ops/ms
# Warmup Iteration   3: 8.929 ops/ms
Iteration   1: 8.886 ops/ms
Iteration   2: 8.948 ops/ms
Iteration   3: 8.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.844 ±(99.9%) 2.375 ops/ms [Average]
  (min, avg, max) = (8.698, 8.844, 8.948), stdev = 0.130
  CI (99.9%): [6.469, 11.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.824 ops/ms
# Warmup Iteration   2: 7.699 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 7.895 ops/ms
Iteration   2: 8.385 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.213 ±(99.9%) 5.024 ops/ms [Average]
  (min, avg, max) = (7.895, 8.213, 8.385), stdev = 0.275
  CI (99.9%): [3.188, 13.237] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ops/ms
# Warmup Iteration   2: 6.004 ops/ms
# Warmup Iteration   3: 6.222 ops/ms
Iteration   1: 6.440 ops/ms
Iteration   2: 6.468 ops/ms
Iteration   3: 6.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.477 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (6.440, 6.477, 6.523), stdev = 0.042
  CI (99.9%): [5.703, 7.251] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.003 ms/op
Iteration   2: 3.898 ±(99.9%) 0.003 ms/op
Iteration   3: 3.897 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.913 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (3.897, 3.913, 3.945), stdev = 0.028
  CI (99.9%): [3.409, 4.417] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.757 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.003 ms/op
Iteration   1: 3.664 ±(99.9%) 0.004 ms/op
Iteration   2: 3.672 ±(99.9%) 0.003 ms/op
Iteration   3: 3.609 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.648 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.609, 3.648, 3.672), stdev = 0.034
  CI (99.9%): [3.028, 4.268] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.174 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.005 ms/op
Iteration   1: 4.012 ±(99.9%) 0.003 ms/op
Iteration   2: 3.929 ±(99.9%) 0.002 ms/op
Iteration   3: 3.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.957 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.929, 3.957, 4.012), stdev = 0.048
  CI (99.9%): [3.091, 4.824] (assumes normal distribution)


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
# Warmup Iteration   1: 7.157 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.504 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.121 ±(99.9%) 0.014 ms/op
Iteration   1: 4.938 ±(99.9%) 0.020 ms/op
Iteration   2: 4.968 ±(99.9%) 0.025 ms/op
Iteration   3: 4.925 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.944 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (4.925, 4.944, 4.968), stdev = 0.022
  CI (99.9%): [4.546, 5.341] (assumes normal distribution)


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
# Warmup Iteration   1: 5.652 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 15.293 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 3.919 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  14.446 ms/op
                 createUser·p0.9999: 20.330 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 4.064 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 19.796 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239269
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5271 
    [ 2.500,  5.000) = 208448 
    [ 5.000,  7.500) = 23678 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.575 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 5.847 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
Iteration   1: 3.557 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  8.290 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 3.657 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  15.525 ms/op
                 existUser·p0.9999: 22.504 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.523 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268480
  mean =      3.578 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9464 
    [ 2.500,  5.000) = 250031 
    [ 5.000,  7.500) = 8094 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.496 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     21.755 ms/op
     p(99.9990) =     22.893 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 5.853 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.850 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  9.387 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.846 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  8.862 ms/op
                 getUser·p0.9999: 22.262 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.374 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246878
  mean =      3.886 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8366 
    [ 2.500,  5.000) = 218051 
    [ 5.000,  7.500) = 19320 
    [ 7.500, 10.000) = 955 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =      9.277 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.890 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 7.331 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.310 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.953 ±(99.9%) 0.016 ms/op
Iteration   1: 4.962 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.685 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  15.518 ms/op
                 listUser·p0.9999: 19.337 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 4.871 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.086 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  19.340 ms/op
                 listUser·p0.9999: 27.417 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   3: 4.904 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.324 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 24.404 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195518
  mean =      4.912 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 398 
    [ 2.500,  5.000) = 128592 
    [ 5.000,  7.500) = 58246 
    [ 7.500, 10.000) = 7149 
    [10.000, 12.500) = 648 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     28.173 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.978 ± 0.503  ops/ms
ClientGrpc.existUser                       thrpt       3   8.844 ± 2.375  ops/ms
ClientGrpc.getUser                         thrpt       3   8.213 ± 5.024  ops/ms
ClientGrpc.listUser                        thrpt       3   6.477 ± 0.774  ops/ms
ClientGrpc.createUser                       avgt       3   3.913 ± 0.504   ms/op
ClientGrpc.existUser                        avgt       3   3.648 ± 0.620   ms/op
ClientGrpc.getUser                          avgt       3   3.957 ± 0.867   ms/op
ClientGrpc.listUser                         avgt       3   4.944 ± 0.397   ms/op
ClientGrpc.createUser                     sample  239269   4.009 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.749           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.143           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.381           ms/op
ClientGrpc.existUser                      sample  268480   3.578 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.626           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.496           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.306           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.755           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.036           ms/op
ClientGrpc.getUser                        sample  246878   3.886 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.940           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.676           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.277           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.281           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.133           ms/op
ClientGrpc.listUser                       sample  195518   4.912 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.233           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.406           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.874           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.001           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
