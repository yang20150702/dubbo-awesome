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
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 7.192 ops/ms
# Warmup Iteration   3: 8.092 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.349 ops/ms
Iteration   3: 8.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.431 ±(99.9%) 3.478 ops/ms [Average]
  (min, avg, max) = (8.294, 8.431, 8.648), stdev = 0.191
  CI (99.9%): [4.953, 11.908] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.902 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 8.870 ops/ms
Iteration   1: 8.520 ops/ms
Iteration   2: 9.033 ops/ms
Iteration   3: 8.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.783 ±(99.9%) 4.686 ops/ms [Average]
  (min, avg, max) = (8.520, 8.783, 9.033), stdev = 0.257
  CI (99.9%): [4.097, 13.468] (assumes normal distribution)


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
# Warmup Iteration   1: 5.259 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 8.227 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.144 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (8.086, 8.144, 8.227), stdev = 0.073
  CI (99.9%): [6.803, 9.484] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ops/ms
# Warmup Iteration   2: 6.219 ops/ms
# Warmup Iteration   3: 6.635 ops/ms
Iteration   1: 6.686 ops/ms
Iteration   2: 6.646 ops/ms
Iteration   3: 6.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.660 ±(99.9%) 0.413 ops/ms [Average]
  (min, avg, max) = (6.646, 6.660, 6.686), stdev = 0.023
  CI (99.9%): [6.247, 7.073] (assumes normal distribution)


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.004 ms/op
Iteration   1: 3.835 ±(99.9%) 0.003 ms/op
Iteration   2: 3.904 ±(99.9%) 0.003 ms/op
Iteration   3: 3.920 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.887 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.835, 3.887, 3.920), stdev = 0.045
  CI (99.9%): [3.064, 4.709] (assumes normal distribution)


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
# Warmup Iteration   1: 4.966 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.003 ms/op
Iteration   1: 3.631 ±(99.9%) 0.003 ms/op
Iteration   2: 3.717 ±(99.9%) 0.002 ms/op
Iteration   3: 3.720 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.689 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.631, 3.689, 3.720), stdev = 0.050
  CI (99.9%): [2.771, 4.607] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.004 ms/op
Iteration   1: 3.827 ±(99.9%) 0.003 ms/op
Iteration   2: 3.855 ±(99.9%) 0.003 ms/op
Iteration   3: 3.761 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.814 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.761, 3.814, 3.855), stdev = 0.048
  CI (99.9%): [2.939, 4.690] (assumes normal distribution)


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
# Warmup Iteration   1: 6.128 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.024 ±(99.9%) 0.013 ms/op
Iteration   1: 4.923 ±(99.9%) 0.009 ms/op
Iteration   2: 4.854 ±(99.9%) 0.011 ms/op
Iteration   3: 4.838 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.871 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (4.838, 4.871, 4.923), stdev = 0.045
  CI (99.9%): [4.049, 5.694] (assumes normal distribution)


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.010 ms/op
Iteration   1: 4.002 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  12.386 ms/op
                 createUser·p0.9999: 18.908 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   2: 3.932 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  11.611 ms/op
                 createUser·p0.9999: 18.936 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 30.856 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 244701
  mean =      3.920 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3802 
    [ 2.500,  5.000) = 223304 
    [ 5.000,  7.500) = 16543 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.876 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     31.559 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 4.950 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.008 ms/op
Iteration   1: 3.579 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.323 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  9.300 ms/op
                 existUser·p0.9999: 20.486 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.503 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  13.307 ms/op
                 existUser·p0.9999: 21.229 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 3.596 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  10.158 ms/op
                 existUser·p0.9999: 22.253 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269626
  mean =      3.559 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6152 
    [ 2.500,  5.000) = 256457 
    [ 5.000,  7.500) = 6304 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     22.597 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.011 ms/op
Iteration   1: 3.804 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  13.172 ms/op
                 getUser·p0.9999: 22.026 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  11.782 ms/op
                 getUser·p0.9999: 21.533 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 3.774 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  8.339 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253269
  mean =      3.789 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5020 
    [ 2.500,  5.000) = 238855 
    [ 5.000,  7.500) = 8427 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     10.116 ms/op
     p(99.9900) =     29.775 ms/op
     p(99.9990) =     30.636 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 6.839 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.931 ±(99.9%) 0.014 ms/op
Iteration   1: 4.942 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  14.931 ms/op
                 listUser·p0.9999: 17.485 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   2: 5.005 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   8.965 ms/op
                 listUser·p0.999:  16.775 ms/op
                 listUser·p0.9999: 20.467 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 4.974 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.161 ms/op
                 listUser·p0.95:   7.000 ms/op
                 listUser·p0.99:   9.128 ms/op
                 listUser·p0.999:  19.529 ms/op
                 listUser·p0.9999: 24.197 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192865
  mean =      4.973 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 125267 
    [ 5.000,  7.500) = 60974 
    [ 7.500, 10.000) = 5343 
    [10.000, 12.500) = 688 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     16.290 ms/op
     p(99.9900) =     22.352 ms/op
     p(99.9990) =     24.480 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.431 ± 3.478  ops/ms
ClientGrpc.existUser                       thrpt       3   8.783 ± 4.686  ops/ms
ClientGrpc.getUser                         thrpt       3   8.144 ± 1.340  ops/ms
ClientGrpc.listUser                        thrpt       3   6.660 ± 0.413  ops/ms
ClientGrpc.createUser                       avgt       3   3.887 ± 0.823   ms/op
ClientGrpc.existUser                        avgt       3   3.689 ± 0.918   ms/op
ClientGrpc.getUser                          avgt       3   3.814 ± 0.876   ms/op
ClientGrpc.listUser                         avgt       3   4.871 ± 0.823   ms/op
ClientGrpc.createUser                     sample  244701   3.920 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.349           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.876           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.131           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.014           ms/op
ClientGrpc.existUser                      sample  269626   3.559 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.323           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.191           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.692           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  253269   3.789 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.116           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.775           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.704           ms/op
ClientGrpc.listUser                       sample  192865   4.973 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.882           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.142           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.290           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.352           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
