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
# Warmup Iteration   1: 3.804 ops/ms
# Warmup Iteration   2: 8.937 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.389 ±(99.9%) 2.042 ops/ms [Average]
  (min, avg, max) = (10.259, 10.389, 10.453), stdev = 0.112
  CI (99.9%): [8.346, 12.431] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ops/ms
# Warmup Iteration   2: 10.370 ops/ms
# Warmup Iteration   3: 10.779 ops/ms
Iteration   1: 10.984 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.768 ±(99.9%) 3.507 ops/ms [Average]
  (min, avg, max) = (10.617, 10.768, 10.984), stdev = 0.192
  CI (99.9%): [7.261, 14.275] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.737 ops/ms
# Warmup Iteration   2: 10.035 ops/ms
# Warmup Iteration   3: 10.202 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 10.254 ops/ms
Iteration   3: 10.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.286 ±(99.9%) 0.809 ops/ms [Average]
  (min, avg, max) = (10.254, 10.286, 10.337), stdev = 0.044
  CI (99.9%): [9.478, 11.095] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.387 ops/ms
# Warmup Iteration   2: 7.682 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 7.793 ops/ms
Iteration   2: 7.670 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.834 ±(99.9%) 3.411 ops/ms [Average]
  (min, avg, max) = (7.670, 7.834, 8.038), stdev = 0.187
  CI (99.9%): [4.423, 11.244] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.259 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.003 ms/op
Iteration   1: 3.079 ±(99.9%) 0.002 ms/op
Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.075 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.063, 3.075, 3.084), stdev = 0.011
  CI (99.9%): [2.878, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.002 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 2.900 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.952 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (2.900, 2.952, 2.986), stdev = 0.046
  CI (99.9%): [2.112, 3.792] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
Iteration   3: 3.080 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.090 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.080, 3.090, 3.108), stdev = 0.016
  CI (99.9%): [2.802, 3.377] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.564 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.017 ms/op
Iteration   1: 4.064 ±(99.9%) 0.011 ms/op
Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
Iteration   3: 3.962 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (3.962, 4.033, 4.072), stdev = 0.061
  CI (99.9%): [2.916, 5.149] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  11.471 ms/op
                 createUser·p0.9999: 14.330 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.754 ms/op
                 createUser·p0.9999: 14.407 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 17.597 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312930
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 951 
    [ 1.250,  2.500) = 17717 
    [ 2.500,  3.750) = 275264 
    [ 3.750,  5.000) = 17365 
    [ 5.000,  6.250) = 929 
    [ 6.250,  7.500) = 242 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      9.929 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     18.189 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.136 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 21.926 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   3: 2.971 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.465 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327082
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33093 
    [ 2.500,  5.000) = 292985 
    [ 5.000,  7.500) = 672 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      8.108 ms/op
     p(99.9900) =     18.529 ms/op
     p(99.9990) =     21.978 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.916 ms/op
                 getUser·p0.9999: 13.994 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.175 ms/op
                 getUser·p0.9999: 14.421 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.823 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312374
  mean =      3.072 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 480 
    [ 1.250,  2.500) = 15586 
    [ 2.500,  3.750) = 279361 
    [ 3.750,  5.000) = 15172 
    [ 5.000,  6.250) = 1230 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.591 ms/op
     p(99.9900) =     17.228 ms/op
     p(99.9990) =     19.198 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 5.856 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
Iteration   1: 4.089 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  12.980 ms/op
                 listUser·p0.9999: 15.308 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 18.061 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.125 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  16.292 ms/op
                 listUser·p0.9999: 21.085 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234979
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2273 
    [ 2.500,  5.000) = 207317 
    [ 5.000,  7.500) = 23913 
    [ 7.500, 10.000) = 964 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     18.858 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.389 ± 2.042  ops/ms
ClientGrpc.existUser                       thrpt       3  10.768 ± 3.507  ops/ms
ClientGrpc.getUser                         thrpt       3  10.286 ± 0.809  ops/ms
ClientGrpc.listUser                        thrpt       3   7.834 ± 3.411  ops/ms
ClientGrpc.createUser                       avgt       3   3.075 ± 0.197   ms/op
ClientGrpc.existUser                        avgt       3   2.952 ± 0.840   ms/op
ClientGrpc.getUser                          avgt       3   3.090 ± 0.287   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 1.117   ms/op
ClientGrpc.createUser                     sample  312930   3.069 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.814           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.857           ms/op
ClientGrpc.existUser                      sample  327082   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.108           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.529           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.987           ms/op
ClientGrpc.getUser                        sample  312374   3.072 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.808           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.591           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.228           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  234979   4.085 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.858           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.660           ms/op
