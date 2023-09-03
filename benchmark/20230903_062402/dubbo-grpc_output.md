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
# Warmup Iteration   1: 4.299 ops/ms
# Warmup Iteration   2: 9.121 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.503 ±(99.9%) 3.259 ops/ms [Average]
  (min, avg, max) = (10.323, 10.503, 10.680), stdev = 0.179
  CI (99.9%): [7.244, 13.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.599 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.999 ops/ms
Iteration   1: 11.059 ops/ms
Iteration   2: 11.248 ops/ms
Iteration   3: 10.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.090 ±(99.9%) 2.653 ops/ms [Average]
  (min, avg, max) = (10.962, 11.090, 11.248), stdev = 0.145
  CI (99.9%): [8.437, 13.743] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.170 ops/ms
# Warmup Iteration   2: 10.195 ops/ms
# Warmup Iteration   3: 10.501 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.757 ops/ms
Iteration   3: 10.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.641 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (10.510, 10.641, 10.757), stdev = 0.124
  CI (99.9%): [8.372, 12.910] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ops/ms
# Warmup Iteration   2: 7.494 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 8.120 ops/ms
Iteration   2: 8.029 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.077 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (8.029, 8.077, 8.120), stdev = 0.046
  CI (99.9%): [7.241, 8.914] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.004 ms/op
Iteration   1: 3.116 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.098, 3.113, 3.126), stdev = 0.014
  CI (99.9%): [2.855, 3.371] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.004 ms/op
Iteration   1: 2.912 ±(99.9%) 0.003 ms/op
Iteration   2: 2.893 ±(99.9%) 0.002 ms/op
Iteration   3: 2.936 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.893, 2.914, 2.936), stdev = 0.022
  CI (99.9%): [2.520, 3.308] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.077 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (3.016, 3.046, 3.077), stdev = 0.031
  CI (99.9%): [2.483, 3.609] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.554 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.012 ms/op
Iteration   1: 3.944 ±(99.9%) 0.009 ms/op
Iteration   2: 3.945 ±(99.9%) 0.011 ms/op
Iteration   3: 3.950 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (3.944, 3.946, 3.950), stdev = 0.003
  CI (99.9%): [3.890, 4.003] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.127 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
Iteration   1: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  8.624 ms/op
                 createUser·p0.9999: 16.753 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.806 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.627 ms/op
                 createUser·p0.9999: 22.923 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313675
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22204 
    [ 2.500,  5.000) = 289145 
    [ 5.000,  7.500) = 1643 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      9.246 ms/op
     p(99.9900) =     21.122 ms/op
     p(99.9990) =     23.031 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.159 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.927 ms/op
                 existUser·p0.9999: 15.188 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   2: 2.951 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.697 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.336 ms/op
                 existUser·p0.9999: 20.780 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   3: 2.906 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 16.237 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325175
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32225 
    [ 2.500,  5.000) = 291543 
    [ 5.000,  7.500) = 1095 
    [ 7.500, 10.000) = 139 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     18.250 ms/op
     p(99.9990) =     21.086 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.674 ms/op
                 getUser·p0.999:  7.867 ms/op
                 getUser·p0.9999: 17.158 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 19.579 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  7.722 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313502
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21388 
    [ 2.500,  5.000) = 289805 
    [ 5.000,  7.500) = 1841 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     21.845 ms/op
     p(99.9990) =     24.600 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.012 ms/op
Iteration   1: 3.963 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.816 ms/op
                 listUser·p0.9999: 17.561 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.139 ms/op
                 listUser·p0.9999: 19.392 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.796 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241665
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2960 
    [ 2.500,  5.000) = 216877 
    [ 5.000,  7.500) = 20256 
    [ 7.500, 10.000) = 1086 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.112 ms/op
     p(99.9900) =     22.812 ms/op
     p(99.9990) =     24.876 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.503 ± 3.259  ops/ms
ClientGrpc.existUser                       thrpt       3  11.090 ± 2.653  ops/ms
ClientGrpc.getUser                         thrpt       3  10.641 ± 2.269  ops/ms
ClientGrpc.listUser                        thrpt       3   8.077 ± 0.837  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.258   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.394   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.563   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.057   ms/op
ClientGrpc.createUser                     sample  313675   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.664           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.246           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.122           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.069           ms/op
ClientGrpc.existUser                      sample  325175   2.952 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.651           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.453           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.250           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  313502   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.791           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.421           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.845           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.674           ms/op
ClientGrpc.listUser                       sample  241665   3.973 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.684           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.112           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.812           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.969           ms/op
