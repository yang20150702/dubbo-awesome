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
# Warmup Iteration   1: 4.150 ops/ms
# Warmup Iteration   2: 8.609 ops/ms
# Warmup Iteration   3: 9.637 ops/ms
Iteration   1: 9.924 ops/ms
Iteration   2: 10.129 ops/ms
Iteration   3: 10.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.038 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (9.924, 10.038, 10.129), stdev = 0.105
  CI (99.9%): [8.128, 11.949] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.026 ops/ms
# Warmup Iteration   2: 10.312 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.545 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.602 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (10.545, 10.602, 10.689), stdev = 0.077
  CI (99.9%): [9.203, 12.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.716 ops/ms
# Warmup Iteration   2: 9.631 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 10.226 ops/ms
Iteration   2: 10.031 ops/ms
Iteration   3: 10.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.124 ±(99.9%) 1.792 ops/ms [Average]
  (min, avg, max) = (10.031, 10.124, 10.226), stdev = 0.098
  CI (99.9%): [8.332, 11.916] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.949 ops/ms
# Warmup Iteration   2: 7.659 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 8.124 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 7.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.056 ±(99.9%) 1.448 ops/ms [Average]
  (min, avg, max) = (7.969, 8.056, 8.124), stdev = 0.079
  CI (99.9%): [6.608, 9.504] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.583 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.002 ms/op
Iteration   1: 3.169 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.159 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.132, 3.159, 3.177), stdev = 0.024
  CI (99.9%): [2.725, 3.594] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.001 ms/op
Iteration   1: 3.047 ±(99.9%) 0.001 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.035 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (3.008, 3.035, 3.052), stdev = 0.024
  CI (99.9%): [2.592, 3.479] (assumes normal distribution)


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.002 ms/op
Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
Iteration   3: 3.144 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.116, 3.142, 3.167), stdev = 0.025
  CI (99.9%): [2.679, 3.606] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.214 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.029 ms/op
Iteration   1: 4.008 ±(99.9%) 0.037 ms/op
Iteration   2: 3.975 ±(99.9%) 0.014 ms/op
Iteration   3: 3.937 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.937, 3.974, 4.008), stdev = 0.035
  CI (99.9%): [3.328, 4.619] (assumes normal distribution)


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.006 ms/op
Iteration   1: 3.183 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.790 ms/op
                 createUser·p0.9999: 12.336 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   2: 3.194 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.770 ms/op
                 createUser·p0.999:  7.463 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  11.773 ms/op
                 createUser·p0.9999: 20.478 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301018
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5734 
    [ 2.500,  5.000) = 293169 
    [ 5.000,  7.500) = 1721 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.003 ms/op
     p(99.9900) =     19.002 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 3.081 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.332 ms/op
                 existUser·p0.9999: 12.603 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.626 ms/op
                 existUser·p0.9999: 14.034 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 3.100 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.767 ms/op
                 existUser·p0.9999: 17.357 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313106
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 14944 
    [ 2.500,  3.750) = 282450 
    [ 3.750,  5.000) = 13961 
    [ 5.000,  6.250) = 789 
    [ 6.250,  7.500) = 478 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     15.030 ms/op
     p(99.9990) =     17.715 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  12.896 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.298 ms/op
                 getUser·p0.9999: 18.536 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.296 ms/op
                 getUser·p0.9999: 20.125 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302937
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6198 
    [ 2.500,  5.000) = 295087 
    [ 5.000,  7.500) = 1178 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.423 ms/op
     p(99.9900) =     19.717 ms/op
     p(99.9990) =     20.572 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.216 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.012 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.845 ms/op
                 listUser·p0.999:  14.026 ms/op
                 listUser·p0.9999: 16.829 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.964 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241146
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2695 
    [ 2.500,  5.000) = 221347 
    [ 5.000,  7.500) = 16188 
    [ 7.500, 10.000) = 511 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.678 ms/op
     p(99.9900) =     22.566 ms/op
     p(99.9990) =     25.972 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.038 ± 1.911  ops/ms
ClientGrpc.existUser                       thrpt       3  10.602 ± 1.399  ops/ms
ClientGrpc.getUser                         thrpt       3  10.124 ± 1.792  ops/ms
ClientGrpc.listUser                        thrpt       3   8.056 ± 1.448  ops/ms
ClientGrpc.createUser                       avgt       3   3.159 ± 0.434   ms/op
ClientGrpc.existUser                        avgt       3   3.035 ± 0.444   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.463   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 0.646   ms/op
ClientGrpc.createUser                     sample  301018   3.189 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.841           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.003           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.002           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.939           ms/op
ClientGrpc.existUser                      sample  313106   3.064 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.868           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.030           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  302937   3.168 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.423           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.717           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  241146   3.978 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.889           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.678           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.566           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.345           ms/op
