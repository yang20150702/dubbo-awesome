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
# Warmup Iteration   1: 2.123 ops/ms
# Warmup Iteration   2: 5.357 ops/ms
# Warmup Iteration   3: 6.745 ops/ms
Iteration   1: 6.962 ops/ms
Iteration   2: 7.146 ops/ms
Iteration   3: 7.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.201 ±(99.9%) 4.930 ops/ms [Average]
  (min, avg, max) = (6.962, 7.201, 7.494), stdev = 0.270
  CI (99.9%): [2.270, 12.131] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.078 ops/ms
# Warmup Iteration   2: 7.140 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 7.948 ops/ms
Iteration   2: 7.894 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.916 ±(99.9%) 0.515 ops/ms [Average]
  (min, avg, max) = (7.894, 7.916, 7.948), stdev = 0.028
  CI (99.9%): [7.401, 8.431] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 6.287 ops/ms
# Warmup Iteration   3: 6.926 ops/ms
Iteration   1: 7.327 ops/ms
Iteration   2: 7.044 ops/ms
Iteration   3: 7.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.140 ±(99.9%) 2.952 ops/ms [Average]
  (min, avg, max) = (7.044, 7.140, 7.327), stdev = 0.162
  CI (99.9%): [4.188, 10.092] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ops/ms
# Warmup Iteration   2: 4.826 ops/ms
# Warmup Iteration   3: 5.567 ops/ms
Iteration   1: 5.574 ops/ms
Iteration   2: 5.641 ops/ms
Iteration   3: 5.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.531 ±(99.9%) 2.482 ops/ms [Average]
  (min, avg, max) = (5.379, 5.531, 5.641), stdev = 0.136
  CI (99.9%): [3.050, 8.013] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.116 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.011 ms/op
Iteration   1: 4.341 ±(99.9%) 0.004 ms/op
Iteration   2: 4.393 ±(99.9%) 0.003 ms/op
Iteration   3: 4.289 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.341 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (4.289, 4.341, 4.393), stdev = 0.052
  CI (99.9%): [3.387, 5.294] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.970 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.006 ms/op
Iteration   1: 4.239 ±(99.9%) 0.004 ms/op
Iteration   2: 4.159 ±(99.9%) 0.002 ms/op
Iteration   3: 4.221 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.207 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (4.159, 4.207, 4.239), stdev = 0.042
  CI (99.9%): [3.441, 4.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.989 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.901 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.647 ±(99.9%) 0.005 ms/op
Iteration   1: 4.505 ±(99.9%) 0.004 ms/op
Iteration   2: 4.421 ±(99.9%) 0.004 ms/op
Iteration   3: 4.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.465 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (4.421, 4.465, 4.505), stdev = 0.042
  CI (99.9%): [3.697, 5.234] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.576 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.807 ±(99.9%) 0.010 ms/op
Iteration   1: 5.721 ±(99.9%) 0.024 ms/op
Iteration   2: 5.821 ±(99.9%) 0.024 ms/op
Iteration   3: 5.688 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.743 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (5.688, 5.743, 5.821), stdev = 0.069
  CI (99.9%): [4.483, 7.004] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.964 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.077 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.014 ms/op
Iteration   1: 4.291 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  9.378 ms/op
                 createUser·p0.9999: 17.287 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 4.492 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.201 ms/op
                 createUser·p0.999:  11.724 ms/op
                 createUser·p0.9999: 17.365 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 4.652 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  16.957 ms/op
                 createUser·p0.9999: 23.802 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214517
  mean =      4.473 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2760 
    [ 2.500,  5.000) = 165119 
    [ 5.000,  7.500) = 44808 
    [ 7.500, 10.000) = 1377 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     13.705 ms/op
     p(99.9900) =     23.447 ms/op
     p(99.9990) =     24.360 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.299 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.009 ms/op
Iteration   1: 4.227 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  11.455 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 4.152 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   4.076 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  11.402 ms/op
                 existUser·p0.9999: 38.724 ms/op
                 existUser·p1.00:   42.467 ms/op

Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   5.210 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  14.956 ms/op
                 existUser·p0.9999: 30.669 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232931
  mean =      4.121 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 208748 
    [ 5.000, 10.000) = 23831 
    [10.000, 15.000) = 195 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 9 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     12.453 ms/op
     p(99.9900) =     38.057 ms/op
     p(99.9990) =     42.140 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.592 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.665 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.011 ms/op
Iteration   1: 4.377 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  11.254 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 4.464 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   4.383 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.841 ms/op
                 getUser·p0.99:   7.302 ms/op
                 getUser·p0.999:  10.513 ms/op
                 getUser·p0.9999: 19.541 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 4.572 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   8.020 ms/op
                 getUser·p0.999:  12.701 ms/op
                 getUser·p0.9999: 18.875 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214710
  mean =      4.470 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2660 
    [ 2.500,  5.000) = 164703 
    [ 5.000,  7.500) = 45017 
    [ 7.500, 10.000) = 1889 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.358 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     11.724 ms/op
     p(99.9900) =     18.892 ms/op
     p(99.9990) =     19.974 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.306 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.907 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.019 ms/op
Iteration   1: 5.423 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.651 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  16.453 ms/op
                 listUser·p0.9999: 22.289 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 5.345 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  16.731 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 5.595 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.258 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.721 ms/op
                 listUser·p0.999:  20.540 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175960
  mean =      5.452 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 68307 
    [ 5.000,  7.500) = 95711 
    [ 7.500, 10.000) = 9871 
    [10.000, 12.500) = 1323 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.905 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     16.811 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     25.861 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.201 ± 4.930  ops/ms
ClientGrpc.existUser                       thrpt       3   7.916 ± 0.515  ops/ms
ClientGrpc.getUser                         thrpt       3   7.140 ± 2.952  ops/ms
ClientGrpc.listUser                        thrpt       3   5.531 ± 2.482  ops/ms
ClientGrpc.createUser                       avgt       3   4.341 ± 0.953   ms/op
ClientGrpc.existUser                        avgt       3   4.207 ± 0.766   ms/op
ClientGrpc.getUser                          avgt       3   4.465 ± 0.768   ms/op
ClientGrpc.listUser                         avgt       3   5.743 ± 1.260   ms/op
ClientGrpc.createUser                     sample  214517   4.473 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.973           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.480           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.283           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.705           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.447           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.543           ms/op
ClientGrpc.existUser                      sample  232931   4.121 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.374           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.652           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.453           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          38.057           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          42.467           ms/op
ClientGrpc.getUser                        sample  214710   4.470 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.100           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.521           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.980           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.619           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.724           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.892           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  175960   5.452 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.331           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.905           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.191           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
