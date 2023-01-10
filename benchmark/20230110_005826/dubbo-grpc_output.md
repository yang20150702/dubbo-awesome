# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 9.320 ops/ms
# Warmup Iteration   3: 10.378 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.210 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.377 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (10.210, 10.377, 10.511), stdev = 0.153
  CI (99.9%): [7.590, 13.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ops/ms
# Warmup Iteration   2: 10.814 ops/ms
# Warmup Iteration   3: 10.967 ops/ms
Iteration   1: 11.046 ops/ms
Iteration   2: 11.121 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.966 ±(99.9%) 3.763 ops/ms [Average]
  (min, avg, max) = (10.732, 10.966, 11.121), stdev = 0.206
  CI (99.9%): [7.204, 14.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.711 ops/ms
# Warmup Iteration   2: 10.099 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.298 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.375 ±(99.9%) 2.302 ops/ms [Average]
  (min, avg, max) = (10.298, 10.375, 10.520), stdev = 0.126
  CI (99.9%): [8.073, 12.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.370 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 7.990 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.093 ±(99.9%) 2.993 ops/ms [Average]
  (min, avg, max) = (7.990, 8.093, 8.282), stdev = 0.164
  CI (99.9%): [5.100, 11.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.173 ±(99.9%) 0.002 ms/op
Iteration   2: 3.169 ±(99.9%) 0.002 ms/op
Iteration   3: 3.171 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.171 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (3.169, 3.171, 3.173), stdev = 0.002
  CI (99.9%): [3.132, 3.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.702 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.971, 3.000, 3.026), stdev = 0.028
  CI (99.9%): [2.497, 3.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 3.068 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (2.976, 3.024, 3.068), stdev = 0.046
  CI (99.9%): [2.189, 3.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.906 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.015 ms/op
Iteration   1: 3.986 ±(99.9%) 0.012 ms/op
Iteration   2: 4.204 ±(99.9%) 0.015 ms/op
Iteration   3: 3.909 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 2.789 ms/op [Average]
  (min, avg, max) = (3.909, 4.033, 4.204), stdev = 0.153
  CI (99.9%): [1.244, 6.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.949 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.171 ms/op
                 createUser·p0.9999: 12.331 ms/op
                 createUser·p1.00:   12.485 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.338 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  11.191 ms/op
                 createUser·p0.9999: 12.766 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.369 ms/op
                 createUser·p0.9999: 15.927 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317163
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1182 
    [ 1.250,  2.500) = 27536 
    [ 2.500,  3.750) = 268776 
    [ 3.750,  5.000) = 18632 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.519 ms/op
     p(99.9900) =     14.996 ms/op
     p(99.9990) =     16.217 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.532 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  7.633 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.258 ms/op
                 existUser·p0.999:  6.685 ms/op
                 existUser·p0.9999: 17.163 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  8.530 ms/op
                 existUser·p0.9999: 16.111 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327039
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2572 
    [ 1.250,  2.500) = 42327 
    [ 2.500,  3.750) = 268686 
    [ 3.750,  5.000) = 12524 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 215 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     17.415 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.051 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  7.417 ms/op
                 getUser·p0.9999: 11.467 ms/op
                 getUser·p1.00:   11.665 ms/op

Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.596 ms/op
                 getUser·p0.9999: 12.975 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.763 ms/op
                 getUser·p0.9999: 16.400 ms/op
                 getUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314134
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1757 
    [ 1.250,  2.500) = 24893 
    [ 2.500,  3.750) = 265036 
    [ 3.750,  5.000) = 21637 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.913 ms/op
     p(99.9900) =     15.574 ms/op
     p(99.9990) =     16.576 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
Iteration   1: 4.177 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  13.088 ms/op
                 listUser·p0.9999: 26.368 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   2: 3.867 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  16.107 ms/op
                 listUser·p0.9999: 20.641 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.123 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.572 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.799 ms/op
                 listUser·p0.9999: 19.807 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236928
  mean =      4.051 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3992 
    [ 2.500,  5.000) = 197179 
    [ 5.000,  7.500) = 34286 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.554 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     26.604 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.377 ± 2.786  ops/ms
ClientGrpc.existUser                       thrpt       3  10.966 ± 3.763  ops/ms
ClientGrpc.getUser                         thrpt       3  10.375 ± 2.302  ops/ms
ClientGrpc.listUser                        thrpt       3   8.093 ± 2.993  ops/ms
ClientGrpc.createUser                       avgt       3   3.171 ± 0.040   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.503   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.835   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 2.789   ms/op
ClientGrpc.createUser                     sample  317163   3.029 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.338           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.519           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.996           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.679           ms/op
ClientGrpc.existUser                      sample  327039   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.531           ms/op
ClientGrpc.getUser                        sample  314134   3.055 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.604           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.913           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.574           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.712           ms/op
ClientGrpc.listUser                       sample  236928   4.051 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.572           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.554           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.708           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.673           ms/op
