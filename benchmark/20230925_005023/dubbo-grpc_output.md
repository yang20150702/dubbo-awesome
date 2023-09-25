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
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 4.808 ops/ms
# Warmup Iteration   3: 6.318 ops/ms
Iteration   1: 6.620 ops/ms
Iteration   2: 6.866 ops/ms
Iteration   3: 6.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.779 ±(99.9%) 2.520 ops/ms [Average]
  (min, avg, max) = (6.620, 6.779, 6.866), stdev = 0.138
  CI (99.9%): [4.260, 9.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ops/ms
# Warmup Iteration   2: 6.725 ops/ms
# Warmup Iteration   3: 7.257 ops/ms
Iteration   1: 7.619 ops/ms
Iteration   2: 7.359 ops/ms
Iteration   3: 7.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.538 ±(99.9%) 2.831 ops/ms [Average]
  (min, avg, max) = (7.359, 7.538, 7.636), stdev = 0.155
  CI (99.9%): [4.707, 10.369] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ops/ms
# Warmup Iteration   2: 6.042 ops/ms
# Warmup Iteration   3: 6.665 ops/ms
Iteration   1: 6.874 ops/ms
Iteration   2: 7.041 ops/ms
Iteration   3: 6.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.873 ±(99.9%) 3.075 ops/ms [Average]
  (min, avg, max) = (6.704, 6.873, 7.041), stdev = 0.169
  CI (99.9%): [3.798, 9.948] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 4.798 ops/ms
# Warmup Iteration   3: 5.228 ops/ms
Iteration   1: 5.154 ops/ms
Iteration   2: 5.298 ops/ms
Iteration   3: 5.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.314 ±(99.9%) 3.080 ops/ms [Average]
  (min, avg, max) = (5.154, 5.314, 5.491), stdev = 0.169
  CI (99.9%): [2.234, 8.394] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.206 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.847 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.018 ms/op
Iteration   1: 4.715 ±(99.9%) 0.005 ms/op
Iteration   2: 4.508 ±(99.9%) 0.003 ms/op
Iteration   3: 4.777 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.666 ±(99.9%) 2.571 ms/op [Average]
  (min, avg, max) = (4.508, 4.666, 4.777), stdev = 0.141
  CI (99.9%): [2.095, 7.237] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.115 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.481 ±(99.9%) 0.002 ms/op
Iteration   1: 4.496 ±(99.9%) 0.004 ms/op
Iteration   2: 4.229 ±(99.9%) 0.003 ms/op
Iteration   3: 4.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.376 ±(99.9%) 2.481 ms/op [Average]
  (min, avg, max) = (4.229, 4.376, 4.496), stdev = 0.136
  CI (99.9%): [1.895, 6.857] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.675 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.003 ms/op
Iteration   1: 4.609 ±(99.9%) 0.003 ms/op
Iteration   2: 4.518 ±(99.9%) 0.004 ms/op
Iteration   3: 4.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.547 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (4.515, 4.547, 4.609), stdev = 0.053
  CI (99.9%): [3.572, 5.523] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.506 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 6.228 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.929 ±(99.9%) 0.017 ms/op
Iteration   1: 5.864 ±(99.9%) 0.019 ms/op
Iteration   2: 5.633 ±(99.9%) 0.014 ms/op
Iteration   3: 5.834 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.777 ±(99.9%) 2.283 ms/op [Average]
  (min, avg, max) = (5.633, 5.777, 5.864), stdev = 0.125
  CI (99.9%): [3.494, 8.060] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.941 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.973 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.015 ms/op
Iteration   1: 4.651 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 15.944 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 4.663 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.956 ms/op
                 createUser·p0.95:   6.685 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  18.364 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   3: 4.746 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   6.021 ms/op
                 createUser·p0.95:   6.857 ms/op
                 createUser·p0.99:   9.949 ms/op
                 createUser·p0.999:  15.083 ms/op
                 createUser·p0.9999: 22.225 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204803
  mean =      4.686 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2506 
    [ 2.500,  5.000) = 141724 
    [ 5.000,  7.500) = 54487 
    [ 7.500, 10.000) = 4462 
    [10.000, 12.500) = 1131 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      9.551 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     21.447 ms/op
     p(99.9990) =     22.803 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.433 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.890 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.607 ±(99.9%) 0.017 ms/op
Iteration   1: 4.522 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.512 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.595 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  18.277 ms/op
                 existUser·p0.9999: 24.569 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 4.538 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.833 ms/op
                 existUser·p0.95:   6.644 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  24.295 ms/op
                 existUser·p0.9999: 32.864 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   3: 4.269 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   4.162 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   8.331 ms/op
                 existUser·p0.999:  13.940 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 216409
  mean =      4.439 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5521 
    [ 2.500,  5.000) = 163997 
    [ 5.000,  7.500) = 41462 
    [ 7.500, 10.000) = 3846 
    [10.000, 12.500) = 896 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     19.254 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     34.057 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.414 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.014 ms/op
Iteration   1: 4.470 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  15.516 ms/op
                 getUser·p0.9999: 19.607 ms/op
                 getUser·p1.00:   20.382 ms/op

Iteration   2: 4.421 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  13.356 ms/op
                 getUser·p0.9999: 16.241 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 4.426 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.587 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  10.349 ms/op
                 getUser·p0.9999: 22.996 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216184
  mean =      4.439 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2607 
    [ 2.500,  5.000) = 165829 
    [ 5.000,  7.500) = 44930 
    [ 7.500, 10.000) = 2327 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.156 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.364 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.228 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.632 ±(99.9%) 0.021 ms/op
Iteration   1: 5.577 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  16.444 ms/op
                 listUser·p0.9999: 22.817 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 5.515 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   5.251 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  19.889 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 5.478 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173811
  mean =      5.523 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 150 
    [ 2.500,  5.000) = 67833 
    [ 5.000,  7.500) = 91355 
    [ 7.500, 10.000) = 11887 
    [10.000, 12.500) = 1972 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     24.301 ms/op
     p(99.9990) =     28.075 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.779 ± 2.520  ops/ms
ClientGrpc.existUser                       thrpt       3   7.538 ± 2.831  ops/ms
ClientGrpc.getUser                         thrpt       3   6.873 ± 3.075  ops/ms
ClientGrpc.listUser                        thrpt       3   5.314 ± 3.080  ops/ms
ClientGrpc.createUser                       avgt       3   4.666 ± 2.571   ms/op
ClientGrpc.existUser                        avgt       3   4.376 ± 2.481   ms/op
ClientGrpc.getUser                          avgt       3   4.547 ± 0.975   ms/op
ClientGrpc.listUser                         avgt       3   5.777 ± 2.283   ms/op
ClientGrpc.createUser                     sample  204803   4.686 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.883           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.972           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.726           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.551           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.335           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.447           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.839           ms/op
ClientGrpc.existUser                      sample  216409   4.439 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.512           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.628           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.349           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.355           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          19.254           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.097           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.210           ms/op
ClientGrpc.getUser                        sample  216184   4.439 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.061           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.128           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.848           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.468           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.774           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  173811   5.523 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.458           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.266           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.617           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.890           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.301           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.148           ms/op
