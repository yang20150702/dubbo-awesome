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
# Warmup Iteration   1: 4.574 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 9.928 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.515 ops/ms
Iteration   3: 10.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.364 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (10.228, 10.364, 10.515), stdev = 0.144
  CI (99.9%): [7.731, 12.996] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.849 ops/ms
Iteration   3: 10.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.746 ±(99.9%) 2.193 ops/ms [Average]
  (min, avg, max) = (10.614, 10.746, 10.849), stdev = 0.120
  CI (99.9%): [8.553, 12.938] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.786 ops/ms
# Warmup Iteration   2: 10.057 ops/ms
# Warmup Iteration   3: 10.425 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.085 ops/ms
Iteration   3: 10.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.320 ±(99.9%) 3.759 ops/ms [Average]
  (min, avg, max) = (10.085, 10.320, 10.469), stdev = 0.206
  CI (99.9%): [6.561, 14.079] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.068 ops/ms
# Warmup Iteration   2: 8.261 ops/ms
# Warmup Iteration   3: 8.360 ops/ms
Iteration   1: 8.363 ops/ms
Iteration   2: 8.553 ops/ms
Iteration   3: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.439 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (8.363, 8.439, 8.553), stdev = 0.100
  CI (99.9%): [6.614, 10.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.110 ±(99.9%) 0.001 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.068, 3.098, 3.117), stdev = 0.027
  CI (99.9%): [2.614, 3.583] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.933 ±(99.9%) 0.002 ms/op
Iteration   2: 2.992 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.959 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.933, 2.959, 2.992), stdev = 0.030
  CI (99.9%): [2.409, 3.510] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 3.120 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.127 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.064, 3.104, 3.127), stdev = 0.035
  CI (99.9%): [2.471, 3.736] (assumes normal distribution)


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
# Warmup Iteration   1: 4.845 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.012 ms/op
Iteration   1: 3.876 ±(99.9%) 0.020 ms/op
Iteration   2: 3.766 ±(99.9%) 0.028 ms/op
Iteration   3: 3.804 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.815 ±(99.9%) 1.023 ms/op [Average]
  (min, avg, max) = (3.766, 3.815, 3.876), stdev = 0.056
  CI (99.9%): [2.793, 4.838] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.750 ms/op
                 createUser·p0.9999: 15.221 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  6.857 ms/op
                 createUser·p0.9999: 15.887 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   3: 3.143 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  11.242 ms/op
                 createUser·p0.9999: 17.295 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310247
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 620 
    [ 1.250,  2.500) = 8232 
    [ 2.500,  3.750) = 284041 
    [ 3.750,  5.000) = 15918 
    [ 5.000,  6.250) = 722 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     17.560 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 11.015 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.010 ms/op
                 existUser·p0.9999: 12.536 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.870 ms/op
                 existUser·p0.9999: 15.385 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321201
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1585 
    [ 1.250,  2.500) = 24771 
    [ 2.500,  3.750) = 281836 
    [ 3.750,  5.000) = 11632 
    [ 5.000,  6.250) = 819 
    [ 6.250,  7.500) = 304 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.922 ms/op
     p(99.9900) =     14.432 ms/op
     p(99.9990) =     15.547 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  12.550 ms/op
                 getUser·p0.9999: 14.495 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.219 ms/op
                 getUser·p0.9999: 15.763 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310610
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 777 
    [ 1.250,  2.500) = 9917 
    [ 2.500,  3.750) = 281978 
    [ 3.750,  5.000) = 16286 
    [ 5.000,  6.250) = 835 
    [ 6.250,  7.500) = 336 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     10.007 ms/op
     p(99.9900) =     17.953 ms/op
     p(99.9990) =     19.785 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 5.072 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
Iteration   1: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  12.846 ms/op
                 listUser·p0.9999: 14.359 ms/op
                 listUser·p1.00:   14.811 ms/op

Iteration   2: 3.812 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 14.543 ms/op
                 listUser·p1.00:   14.778 ms/op

Iteration   3: 3.870 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.865 ms/op
                 listUser·p0.9999: 20.340 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250513
  mean =      3.831 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4023 
    [ 2.500,  5.000) = 232231 
    [ 5.000,  7.500) = 13443 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     19.459 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.364 ± 2.633  ops/ms
ClientGrpc.existUser                       thrpt       3  10.746 ± 2.193  ops/ms
ClientGrpc.getUser                         thrpt       3  10.320 ± 3.759  ops/ms
ClientGrpc.listUser                        thrpt       3   8.439 ± 1.825  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.485   ms/op
ClientGrpc.existUser                        avgt       3   2.959 ± 0.550   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.633   ms/op
ClientGrpc.listUser                         avgt       3   3.815 ± 1.023   ms/op
ClientGrpc.createUser                     sample  310247   3.094 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.876           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.695           ms/op
ClientGrpc.existUser                      sample  321201   2.986 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.922           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.432           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.302           ms/op
ClientGrpc.getUser                        sample  310610   3.091 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.007           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.953           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.956           ms/op
ClientGrpc.listUser                       sample  250513   3.831 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.956           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.423           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.025           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.459           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.594           ms/op
