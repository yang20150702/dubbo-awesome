# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ops/ms
# Warmup Iteration   2: 9.319 ops/ms
# Warmup Iteration   3: 10.255 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.820 ops/ms
Iteration   3: 10.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.641 ±(99.9%) 2.838 ops/ms [Average]
  (min, avg, max) = (10.539, 10.641, 10.820), stdev = 0.156
  CI (99.9%): [7.803, 13.479] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.985 ops/ms
# Warmup Iteration   2: 10.767 ops/ms
# Warmup Iteration   3: 11.133 ops/ms
Iteration   1: 11.130 ops/ms
Iteration   2: 11.052 ops/ms
Iteration   3: 11.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.110 ±(99.9%) 0.920 ops/ms [Average]
  (min, avg, max) = (11.052, 11.110, 11.147), stdev = 0.050
  CI (99.9%): [10.189, 12.030] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.821 ops/ms
# Warmup Iteration   2: 10.059 ops/ms
# Warmup Iteration   3: 10.556 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.724 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (10.605, 10.724, 10.843), stdev = 0.119
  CI (99.9%): [8.559, 12.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.365 ops/ms
# Warmup Iteration   2: 8.058 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.559 ops/ms
Iteration   3: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.410 ±(99.9%) 2.558 ops/ms [Average]
  (min, avg, max) = (8.280, 8.410, 8.559), stdev = 0.140
  CI (99.9%): [5.852, 10.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.002 ms/op
Iteration   1: 2.999 ±(99.9%) 0.011 ms/op
Iteration   2: 3.000 ±(99.9%) 0.003 ms/op
Iteration   3: 3.066 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.999, 3.022, 3.066), stdev = 0.038
  CI (99.9%): [2.320, 3.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.003 ms/op
Iteration   1: 2.852 ±(99.9%) 0.003 ms/op
Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
Iteration   3: 2.915 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (2.852, 2.892, 2.915), stdev = 0.035
  CI (99.9%): [2.250, 3.535] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 2.958 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.004 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.945 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.926, 2.945, 2.958), stdev = 0.017
  CI (99.9%): [2.640, 3.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.123 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.013 ms/op
Iteration   1: 3.879 ±(99.9%) 0.024 ms/op
Iteration   2: 3.885 ±(99.9%) 0.014 ms/op
Iteration   3: 3.766 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.843 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.766, 3.843, 3.885), stdev = 0.067
  CI (99.9%): [2.626, 5.060] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  9.478 ms/op
                 createUser·p0.9999: 16.612 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  10.262 ms/op
                 createUser·p0.9999: 17.513 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  10.372 ms/op
                 createUser·p0.9999: 31.502 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318886
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23235 
    [ 2.500,  5.000) = 294287 
    [ 5.000,  7.500) = 894 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     10.178 ms/op
     p(99.9900) =     31.006 ms/op
     p(99.9990) =     32.249 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.005 ms/op
Iteration   1: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  8.956 ms/op
                 existUser·p0.9999: 13.678 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.853 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.281 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  7.692 ms/op
                 existUser·p0.9999: 15.090 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.742 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334470
  mean =      2.871 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44114 
    [ 2.500,  5.000) = 289379 
    [ 5.000,  7.500) = 607 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     16.696 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.436 ms/op
                 getUser·p0.9999: 13.838 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.922 ms/op
                 getUser·p0.9999: 16.144 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 16.230 ms/op
                 getUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321411
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 605 
    [ 1.250,  2.500) = 31096 
    [ 2.500,  3.750) = 275136 
    [ 3.750,  5.000) = 13078 
    [ 5.000,  6.250) = 960 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.288 ms/op
     p(99.9900) =     16.103 ms/op
     p(99.9990) =     16.488 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.046 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.200 ms/op
                 listUser·p0.9999: 17.641 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.490 ms/op
                 listUser·p0.9999: 15.904 ms/op
                 listUser·p1.00:   16.237 ms/op

Iteration   3: 3.824 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.279 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 31.085 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248262
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4572 
    [ 2.500,  5.000) = 223810 
    [ 5.000,  7.500) = 18811 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     31.426 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.641 ± 2.838  ops/ms
ClientGrpc.existUser                       thrpt       3  11.110 ± 0.920  ops/ms
ClientGrpc.getUser                         thrpt       3  10.724 ± 2.165  ops/ms
ClientGrpc.listUser                        thrpt       3   8.410 ± 2.558  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.701   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.643   ms/op
ClientGrpc.getUser                          avgt       3   2.945 ± 0.305   ms/op
ClientGrpc.listUser                         avgt       3   3.843 ± 1.217   ms/op
ClientGrpc.createUser                     sample  318886   3.012 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.806           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.178           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.006           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.670           ms/op
ClientGrpc.existUser                      sample  334470   2.871 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.281           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.807           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.696           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.100           ms/op
ClientGrpc.getUser                        sample  321411   2.986 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.813           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.288           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.103           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.548           ms/op
ClientGrpc.listUser                       sample  248262   3.863 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.278           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
