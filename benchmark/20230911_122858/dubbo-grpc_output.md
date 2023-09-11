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
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 4.865 ops/ms
# Warmup Iteration   3: 6.882 ops/ms
Iteration   1: 7.108 ops/ms
Iteration   2: 7.223 ops/ms
Iteration   3: 7.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.142 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (7.095, 7.142, 7.223), stdev = 0.070
  CI (99.9%): [5.856, 8.428] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ops/ms
# Warmup Iteration   2: 7.163 ops/ms
# Warmup Iteration   3: 7.762 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 7.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.808 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (7.664, 7.808, 7.952), stdev = 0.144
  CI (99.9%): [5.176, 10.439] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.611 ops/ms
# Warmup Iteration   2: 7.171 ops/ms
# Warmup Iteration   3: 7.642 ops/ms
Iteration   1: 7.522 ops/ms
Iteration   2: 7.436 ops/ms
Iteration   3: 7.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.462 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (7.428, 7.462, 7.522), stdev = 0.052
  CI (99.9%): [6.511, 8.413] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.257 ops/ms
# Warmup Iteration   2: 4.787 ops/ms
# Warmup Iteration   3: 5.479 ops/ms
Iteration   1: 5.435 ops/ms
Iteration   2: 5.487 ops/ms
Iteration   3: 5.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.524 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (5.435, 5.524, 5.648), stdev = 0.111
  CI (99.9%): [3.496, 7.551] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.398 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.003 ms/op
Iteration   1: 4.512 ±(99.9%) 0.004 ms/op
Iteration   2: 4.526 ±(99.9%) 0.004 ms/op
Iteration   3: 4.392 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.477 ±(99.9%) 1.340 ms/op [Average]
  (min, avg, max) = (4.392, 4.477, 4.526), stdev = 0.073
  CI (99.9%): [3.136, 5.817] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.073 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.004 ms/op
Iteration   1: 4.040 ±(99.9%) 0.002 ms/op
Iteration   2: 4.346 ±(99.9%) 0.004 ms/op
Iteration   3: 4.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.135 ±(99.9%) 3.347 ms/op [Average]
  (min, avg, max) = (4.019, 4.135, 4.346), stdev = 0.183
  CI (99.9%): [0.788, 7.482] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.454 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.586 ±(99.9%) 0.006 ms/op
Iteration   1: 4.381 ±(99.9%) 0.004 ms/op
Iteration   2: 4.405 ±(99.9%) 0.005 ms/op
Iteration   3: 4.146 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.311 ±(99.9%) 2.609 ms/op [Average]
  (min, avg, max) = (4.146, 4.311, 4.405), stdev = 0.143
  CI (99.9%): [1.702, 6.919] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.484 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.058 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.628 ±(99.9%) 0.015 ms/op
Iteration   1: 5.701 ±(99.9%) 0.037 ms/op
Iteration   2: 5.777 ±(99.9%) 0.025 ms/op
Iteration   3: 5.718 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.732 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (5.701, 5.732, 5.777), stdev = 0.040
  CI (99.9%): [5.003, 6.461] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.814 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.452 ±(99.9%) 0.014 ms/op
Iteration   1: 4.509 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.316 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  14.123 ms/op
                 createUser·p0.9999: 17.954 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   2: 4.675 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   4.481 ms/op
                 createUser·p0.90:   5.980 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  13.678 ms/op
                 createUser·p0.9999: 20.391 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 4.528 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.702 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   7.698 ms/op
                 createUser·p0.999:  22.266 ms/op
                 createUser·p0.9999: 28.830 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210224
  mean =      4.569 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2342 
    [ 2.500,  5.000) = 151039 
    [ 5.000,  7.500) = 53454 
    [ 7.500, 10.000) = 2452 
    [10.000, 12.500) = 524 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     28.376 ms/op
     p(99.9990) =     29.078 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 6.762 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.013 ms/op
Iteration   1: 4.182 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.349 ms/op
                 existUser·p0.95:   5.947 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  14.909 ms/op
                 existUser·p0.9999: 16.744 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 3.938 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  10.104 ms/op
                 existUser·p0.9999: 20.775 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 4.017 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  13.048 ms/op
                 existUser·p0.9999: 19.467 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237344
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5932 
    [ 2.500,  5.000) = 202475 
    [ 5.000,  7.500) = 26641 
    [ 7.500, 10.000) = 1647 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     13.014 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 6.776 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.378 ±(99.9%) 0.014 ms/op
Iteration   1: 4.448 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.689 ms/op
                 getUser·p0.999:  15.175 ms/op
                 getUser·p0.9999: 18.141 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 4.491 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  14.306 ms/op
                 getUser·p0.9999: 18.670 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 4.555 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  14.038 ms/op
                 getUser·p0.9999: 21.133 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 213429
  mean =      4.498 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4103 
    [ 2.500,  5.000) = 155725 
    [ 5.000,  7.500) = 49564 
    [ 7.500, 10.000) = 2973 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     14.329 ms/op
     p(99.9900) =     20.796 ms/op
     p(99.9990) =     21.347 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 8.709 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 6.394 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.757 ±(99.9%) 0.023 ms/op
Iteration   1: 5.612 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  16.186 ms/op
                 listUser·p0.9999: 24.179 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 5.691 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  21.856 ms/op
                 listUser·p0.9999: 25.326 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 5.713 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 29.799 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169298
  mean =      5.672 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 59717 
    [ 5.000,  7.500) = 93018 
    [ 7.500, 10.000) = 13007 
    [10.000, 12.500) = 2419 
    [12.500, 15.000) = 630 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     21.696 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.141 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.142 ± 1.286  ops/ms
ClientGrpc.existUser                       thrpt       3   7.808 ± 2.632  ops/ms
ClientGrpc.getUser                         thrpt       3   7.462 ± 0.951  ops/ms
ClientGrpc.listUser                        thrpt       3   5.524 ± 2.027  ops/ms
ClientGrpc.createUser                       avgt       3   4.477 ± 1.340   ms/op
ClientGrpc.existUser                        avgt       3   4.135 ± 3.347   ms/op
ClientGrpc.getUser                          avgt       3   4.311 ± 2.609   ms/op
ClientGrpc.listUser                         avgt       3   5.732 ± 0.729   ms/op
ClientGrpc.createUser                     sample  210224   4.569 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.135           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.357           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.241           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.139           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.376           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.164           ms/op
ClientGrpc.existUser                      sample  237344   4.043 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.745           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.710           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.455           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.014           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.300           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  213429   4.498 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.137           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.398           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.329           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.796           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  169298   5.672 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.034           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.536           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.338           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.000           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.278           ms/op
