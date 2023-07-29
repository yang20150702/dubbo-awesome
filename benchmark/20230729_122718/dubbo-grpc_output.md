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
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 7.245 ops/ms
# Warmup Iteration   3: 8.410 ops/ms
Iteration   1: 8.598 ops/ms
Iteration   2: 8.627 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.612 ±(99.9%) 0.261 ops/ms [Average]
  (min, avg, max) = (8.598, 8.612, 8.627), stdev = 0.014
  CI (99.9%): [8.351, 8.873] (assumes normal distribution)


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
# Warmup Iteration   1: 5.667 ops/ms
# Warmup Iteration   2: 8.545 ops/ms
# Warmup Iteration   3: 8.833 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 9.190 ops/ms
Iteration   3: 8.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.135 ±(99.9%) 4.728 ops/ms [Average]
  (min, avg, max) = (8.853, 9.135, 9.362), stdev = 0.259
  CI (99.9%): [4.407, 13.863] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.407 ops/ms
# Warmup Iteration   2: 8.246 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 8.628 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.604 ±(99.9%) 0.416 ops/ms [Average]
  (min, avg, max) = (8.583, 8.604, 8.628), stdev = 0.023
  CI (99.9%): [8.188, 9.020] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.670 ops/ms
# Warmup Iteration   2: 6.278 ops/ms
# Warmup Iteration   3: 6.452 ops/ms
Iteration   1: 6.505 ops/ms
Iteration   2: 6.592 ops/ms
Iteration   3: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.544 ±(99.9%) 0.806 ops/ms [Average]
  (min, avg, max) = (6.505, 6.544, 6.592), stdev = 0.044
  CI (99.9%): [5.738, 7.350] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.387 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.003 ms/op
Iteration   1: 3.694 ±(99.9%) 0.004 ms/op
Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
Iteration   3: 3.609 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.678 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.609, 3.678, 3.729), stdev = 0.062
  CI (99.9%): [2.548, 4.807] (assumes normal distribution)


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
# Warmup Iteration   1: 5.024 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.004 ms/op
Iteration   1: 3.548 ±(99.9%) 0.003 ms/op
Iteration   2: 3.489 ±(99.9%) 0.003 ms/op
Iteration   3: 3.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.513 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.489, 3.513, 3.548), stdev = 0.031
  CI (99.9%): [2.953, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.004 ms/op
Iteration   1: 3.791 ±(99.9%) 0.003 ms/op
Iteration   2: 3.653 ±(99.9%) 0.005 ms/op
Iteration   3: 3.659 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.701 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (3.653, 3.701, 3.791), stdev = 0.078
  CI (99.9%): [2.282, 5.120] (assumes normal distribution)


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
# Warmup Iteration   1: 7.024 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.058 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.850 ±(99.9%) 0.016 ms/op
Iteration   1: 4.771 ±(99.9%) 0.014 ms/op
Iteration   2: 4.693 ±(99.9%) 0.015 ms/op
Iteration   3: 4.940 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.802 ±(99.9%) 2.299 ms/op [Average]
  (min, avg, max) = (4.693, 4.802, 4.940), stdev = 0.126
  CI (99.9%): [2.503, 7.100] (assumes normal distribution)


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.731 ±(99.9%) 0.009 ms/op
Iteration   1: 3.684 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   7.076 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 17.541 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   2: 3.741 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  10.422 ms/op
                 createUser·p0.9999: 24.296 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.714 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  17.643 ms/op
                 createUser·p0.9999: 20.668 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 258784
  mean =      3.713 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11471 
    [ 2.500,  5.000) = 234698 
    [ 5.000,  7.500) = 10654 
    [ 7.500, 10.000) = 1170 
    [10.000, 12.500) = 469 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     23.564 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 5.254 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.009 ms/op
Iteration   1: 3.628 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  12.852 ms/op
                 existUser·p0.9999: 17.237 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 3.628 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.606 ms/op
                 existUser·p0.999:  9.598 ms/op
                 existUser·p0.9999: 27.052 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 3.564 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  11.717 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266274
  mean =      3.606 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13011 
    [ 2.500,  5.000) = 241731 
    [ 5.000,  7.500) = 10050 
    [ 7.500, 10.000) = 952 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     11.563 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     28.407 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.010 ms/op
Iteration   1: 3.712 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.065 ms/op
                 getUser·p0.999:  11.546 ms/op
                 getUser·p0.9999: 15.719 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 3.749 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  12.971 ms/op
                 getUser·p0.9999: 16.793 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.740 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.901 ms/op
                 getUser·p0.999:  13.042 ms/op
                 getUser·p0.9999: 30.245 ms/op
                 getUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257116
  mean =      3.734 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8200 
    [ 2.500,  5.000) = 236274 
    [ 5.000,  7.500) = 10834 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     28.321 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 6.788 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.964 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.016 ms/op
Iteration   1: 4.889 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 26.640 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   2: 4.847 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 19.831 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 4.944 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  29.688 ms/op
                 listUser·p0.9999: 34.020 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196137
  mean =      4.893 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 511 
    [ 2.500,  5.000) = 137183 
    [ 5.000,  7.500) = 50055 
    [ 7.500, 10.000) = 6633 
    [10.000, 12.500) = 1248 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     32.420 ms/op
     p(99.9990) =     34.543 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.612 ± 0.261  ops/ms
ClientGrpc.existUser                       thrpt       3   9.135 ± 4.728  ops/ms
ClientGrpc.getUser                         thrpt       3   8.604 ± 0.416  ops/ms
ClientGrpc.listUser                        thrpt       3   6.544 ± 0.806  ops/ms
ClientGrpc.createUser                       avgt       3   3.678 ± 1.129   ms/op
ClientGrpc.existUser                        avgt       3   3.513 ± 0.561   ms/op
ClientGrpc.getUser                          avgt       3   3.701 ± 1.419   ms/op
ClientGrpc.listUser                         avgt       3   4.802 ± 2.299   ms/op
ClientGrpc.createUser                     sample  258784   3.713 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.955           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.894           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.564           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.805           ms/op
ClientGrpc.existUser                      sample  266274   3.606 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.611           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.563           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.313           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.786           ms/op
ClientGrpc.getUser                        sample  257116   3.734 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.887           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.004           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.747           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.321           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.605           ms/op
ClientGrpc.listUser                       sample  196137   4.893 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.174           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.390           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.367           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.420           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.669           ms/op
