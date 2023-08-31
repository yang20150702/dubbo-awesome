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
# Warmup Iteration   1: 3.877 ops/ms
# Warmup Iteration   2: 8.682 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 10.054 ops/ms
Iteration   2: 10.198 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.189 ±(99.9%) 2.396 ops/ms [Average]
  (min, avg, max) = (10.054, 10.189, 10.316), stdev = 0.131
  CI (99.9%): [7.793, 12.586] (assumes normal distribution)


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
# Warmup Iteration   1: 7.491 ops/ms
# Warmup Iteration   2: 10.355 ops/ms
# Warmup Iteration   3: 10.682 ops/ms
Iteration   1: 10.944 ops/ms
Iteration   2: 11.049 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.916 ±(99.9%) 2.713 ops/ms [Average]
  (min, avg, max) = (10.755, 10.916, 11.049), stdev = 0.149
  CI (99.9%): [8.202, 13.629] (assumes normal distribution)


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
# Warmup Iteration   1: 7.050 ops/ms
# Warmup Iteration   2: 9.681 ops/ms
# Warmup Iteration   3: 10.095 ops/ms
Iteration   1: 10.085 ops/ms
Iteration   2: 10.326 ops/ms
Iteration   3: 10.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.273 ±(99.9%) 3.053 ops/ms [Average]
  (min, avg, max) = (10.085, 10.273, 10.407), stdev = 0.167
  CI (99.9%): [7.219, 13.326] (assumes normal distribution)


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
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 7.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.906 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (7.836, 7.906, 7.966), stdev = 0.065
  CI (99.9%): [6.711, 9.100] (assumes normal distribution)


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.002 ms/op
Iteration   1: 3.129 ±(99.9%) 0.002 ms/op
Iteration   2: 3.164 ±(99.9%) 0.001 ms/op
Iteration   3: 3.106 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.106, 3.133, 3.164), stdev = 0.029
  CI (99.9%): [2.608, 3.658] (assumes normal distribution)


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.002 ms/op
Iteration   1: 2.911 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.940 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.944 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (2.911, 2.944, 2.981), stdev = 0.035
  CI (99.9%): [2.301, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.004 ms/op
Iteration   1: 3.154 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
Iteration   3: 3.161 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.158 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (3.154, 3.158, 3.161), stdev = 0.004
  CI (99.9%): [3.088, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 5.411 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.008 ms/op
Iteration   1: 3.901 ±(99.9%) 0.015 ms/op
Iteration   2: 4.087 ±(99.9%) 0.019 ms/op
Iteration   3: 3.897 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 1.979 ms/op [Average]
  (min, avg, max) = (3.897, 3.962, 4.087), stdev = 0.108
  CI (99.9%): [1.983, 5.940] (assumes normal distribution)


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
Iteration   1: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 16.713 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.810 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.164 ms/op
                 createUser·p0.9999: 31.818 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306192
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15537 
    [ 2.500,  5.000) = 288208 
    [ 5.000,  7.500) = 1929 
    [ 7.500, 10.000) = 200 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     10.266 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     32.176 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.835 ms/op
                 existUser·p0.9999: 15.136 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 16.482 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.496 ms/op
                 existUser·p0.9999: 16.624 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319338
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1804 
    [ 1.250,  2.500) = 27424 
    [ 2.500,  3.750) = 271405 
    [ 3.750,  5.000) = 16530 
    [ 5.000,  6.250) = 1092 
    [ 6.250,  7.500) = 608 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.247 ms/op
     p(99.9900) =     16.271 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.100 ms/op
                 getUser·p0.9999: 13.878 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 3.227 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.217 ms/op
                 getUser·p0.9999: 15.227 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   3: 3.235 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.187 ms/op
                 getUser·p0.999:  8.407 ms/op
                 getUser·p0.9999: 19.672 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297650
  mean =      3.224 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8600 
    [ 2.500,  5.000) = 286093 
    [ 5.000,  7.500) = 2426 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.993 ms/op
     p(99.9000) =      8.339 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     20.522 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 6.008 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.012 ms/op
Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  13.951 ms/op
                 listUser·p0.9999: 16.761 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   2: 4.089 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.774 ms/op
                 listUser·p0.9999: 24.621 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  17.528 ms/op
                 listUser·p0.9999: 26.597 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233126
  mean =      4.116 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2455 
    [ 2.500,  5.000) = 202467 
    [ 5.000,  7.500) = 26110 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     28.104 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.189 ± 2.396  ops/ms
ClientGrpc.existUser                       thrpt       3  10.916 ± 2.713  ops/ms
ClientGrpc.getUser                         thrpt       3  10.273 ± 3.053  ops/ms
ClientGrpc.listUser                        thrpt       3   7.906 ± 1.194  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.525   ms/op
ClientGrpc.existUser                        avgt       3   2.944 ± 0.643   ms/op
ClientGrpc.getUser                          avgt       3   3.158 ± 0.069   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 1.979   ms/op
ClientGrpc.createUser                     sample  306192   3.134 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.656           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.266           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.671           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.375           ms/op
ClientGrpc.existUser                      sample  319338   3.007 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.601           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.247           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.271           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.007           ms/op
ClientGrpc.getUser                        sample  297650   3.224 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.649           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.993           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.339           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.678           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  233126   4.116 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.032           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.302           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.247           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
