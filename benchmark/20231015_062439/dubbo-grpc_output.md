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
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 8.486 ops/ms
# Warmup Iteration   3: 9.679 ops/ms
Iteration   1: 10.196 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 10.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.154 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (10.114, 10.154, 10.196), stdev = 0.041
  CI (99.9%): [9.412, 10.895] (assumes normal distribution)


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
# Warmup Iteration   1: 7.056 ops/ms
# Warmup Iteration   2: 10.032 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.712 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (10.635, 10.712, 10.792), stdev = 0.079
  CI (99.9%): [9.273, 12.150] (assumes normal distribution)


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
# Warmup Iteration   1: 6.361 ops/ms
# Warmup Iteration   2: 9.450 ops/ms
# Warmup Iteration   3: 10.016 ops/ms
Iteration   1: 10.035 ops/ms
Iteration   2: 10.233 ops/ms
Iteration   3: 10.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.155 ±(99.9%) 1.925 ops/ms [Average]
  (min, avg, max) = (10.035, 10.155, 10.233), stdev = 0.106
  CI (99.9%): [8.230, 12.080] (assumes normal distribution)


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
# Warmup Iteration   1: 5.516 ops/ms
# Warmup Iteration   2: 7.532 ops/ms
# Warmup Iteration   3: 7.875 ops/ms
Iteration   1: 7.901 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 8.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.953 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (7.901, 7.953, 8.031), stdev = 0.069
  CI (99.9%): [6.701, 9.206] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.015 ms/op
Iteration   1: 3.184 ±(99.9%) 0.005 ms/op
Iteration   2: 3.158 ±(99.9%) 0.004 ms/op
Iteration   3: 3.157 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.166 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.157, 3.166, 3.184), stdev = 0.015
  CI (99.9%): [2.887, 3.445] (assumes normal distribution)


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.031 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.010, 3.031, 3.067), stdev = 0.032
  CI (99.9%): [2.452, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.003 ms/op
Iteration   1: 3.188 ±(99.9%) 0.002 ms/op
Iteration   2: 3.169 ±(99.9%) 0.003 ms/op
Iteration   3: 3.148 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.168 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.148, 3.168, 3.188), stdev = 0.020
  CI (99.9%): [2.803, 3.534] (assumes normal distribution)


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
# Warmup Iteration   1: 5.622 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.030 ms/op
Iteration   1: 4.022 ±(99.9%) 0.017 ms/op
Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
Iteration   3: 4.005 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 1.649 ms/op [Average]
  (min, avg, max) = (3.857, 3.961, 4.022), stdev = 0.090
  CI (99.9%): [2.313, 5.610] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  9.464 ms/op
                 createUser·p0.9999: 15.146 ms/op
                 createUser·p1.00:   15.892 ms/op

Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  7.910 ms/op
                 createUser·p0.9999: 16.180 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.429 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.003 ms/op
                 createUser·p0.999:  16.220 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302295
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10944 
    [ 2.500,  5.000) = 288629 
    [ 5.000,  7.500) = 1974 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     11.857 ms/op
     p(99.9900) =     18.108 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.806 ms/op
                 existUser·p0.99:   4.445 ms/op
                 existUser·p0.999:  9.952 ms/op
                 existUser·p0.9999: 24.838 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  13.350 ms/op
                 existUser·p0.9999: 22.517 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.929 ms/op
                 existUser·p0.9999: 26.214 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315956
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21205 
    [ 2.500,  5.000) = 292967 
    [ 5.000,  7.500) = 1276 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     11.192 ms/op
     p(99.9900) =     25.310 ms/op
     p(99.9990) =     26.929 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  9.103 ms/op
                 getUser·p0.9999: 16.564 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.776 ms/op
                 getUser·p0.999:  12.845 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.569 ms/op
                 getUser·p0.9999: 25.473 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305059
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15308 
    [ 2.500,  5.000) = 287235 
    [ 5.000,  7.500) = 1935 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     19.120 ms/op
     p(99.9990) =     25.783 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  14.596 ms/op
                 listUser·p0.9999: 17.875 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.870 ms/op
                 listUser·p0.999:  15.205 ms/op
                 listUser·p0.9999: 17.040 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.980 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  24.716 ms/op
                 listUser·p0.9999: 33.485 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238650
  mean =      4.019 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1854 
    [ 2.500,  5.000) = 220735 
    [ 5.000,  7.500) = 14324 
    [ 7.500, 10.000) = 1130 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.767 ms/op
     p(99.9900) =     29.734 ms/op
     p(99.9990) =     33.922 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.154 ± 0.741  ops/ms
ClientGrpc.existUser                       thrpt       3  10.712 ± 1.438  ops/ms
ClientGrpc.getUser                         thrpt       3  10.155 ± 1.925  ops/ms
ClientGrpc.listUser                        thrpt       3   7.953 ± 1.253  ops/ms
ClientGrpc.createUser                       avgt       3   3.166 ± 0.279   ms/op
ClientGrpc.existUser                        avgt       3   3.031 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.168 ± 0.365   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 1.649   ms/op
ClientGrpc.createUser                     sample  302295   3.176 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.429           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.857           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.108           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.872           ms/op
ClientGrpc.existUser                      sample  315956   3.037 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.583           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.192           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.310           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  305059   3.145 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.767           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.798           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.120           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.116           ms/op
ClientGrpc.listUser                       sample  238650   4.019 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.899           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.767           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.734           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.079           ms/op
