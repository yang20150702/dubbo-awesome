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
# Warmup Iteration   1: 3.912 ops/ms
# Warmup Iteration   2: 9.012 ops/ms
# Warmup Iteration   3: 9.810 ops/ms
Iteration   1: 10.399 ops/ms
Iteration   2: 10.418 ops/ms
Iteration   3: 10.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.395 ±(99.9%) 0.449 ops/ms [Average]
  (min, avg, max) = (10.369, 10.395, 10.418), stdev = 0.025
  CI (99.9%): [9.946, 10.844] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.983 ops/ms
# Warmup Iteration   2: 10.396 ops/ms
# Warmup Iteration   3: 10.665 ops/ms
Iteration   1: 10.853 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.766 ±(99.9%) 2.376 ops/ms [Average]
  (min, avg, max) = (10.616, 10.766, 10.853), stdev = 0.130
  CI (99.9%): [8.390, 13.142] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.382 ops/ms
# Warmup Iteration   2: 9.640 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.485 ±(99.9%) 2.230 ops/ms [Average]
  (min, avg, max) = (10.406, 10.485, 10.626), stdev = 0.122
  CI (99.9%): [8.256, 12.715] (assumes normal distribution)


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
# Warmup Iteration   1: 5.282 ops/ms
# Warmup Iteration   2: 7.381 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 7.804 ops/ms
Iteration   2: 8.008 ops/ms
Iteration   3: 7.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.903 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (7.804, 7.903, 8.008), stdev = 0.102
  CI (99.9%): [6.042, 9.764] (assumes normal distribution)


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.090 ±(99.9%) 1.242 ms/op [Average]
  (min, avg, max) = (3.012, 3.090, 3.137), stdev = 0.068
  CI (99.9%): [1.848, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.002 ms/op
Iteration   1: 2.907 ±(99.9%) 0.001 ms/op
Iteration   2: 2.870 ±(99.9%) 0.002 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (2.870, 2.908, 2.949), stdev = 0.040
  CI (99.9%): [2.186, 3.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.004 ms/op
Iteration   1: 3.062 ±(99.9%) 0.004 ms/op
Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (3.048, 3.059, 3.067), stdev = 0.010
  CI (99.9%): [2.881, 3.237] (assumes normal distribution)


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
# Warmup Iteration   1: 5.344 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.032 ms/op
Iteration   1: 3.908 ±(99.9%) 0.015 ms/op
Iteration   2: 3.899 ±(99.9%) 0.021 ms/op
Iteration   3: 3.896 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.901 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (3.896, 3.901, 3.908), stdev = 0.006
  CI (99.9%): [3.786, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  6.816 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  10.508 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  8.658 ms/op
                 createUser·p0.9999: 21.648 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310222
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21097 
    [ 2.500,  5.000) = 286785 
    [ 5.000,  7.500) = 1774 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     22.017 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
Iteration   1: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.580 ms/op
                 existUser·p0.999:  7.859 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.824 ms/op
                 existUser·p0.9999: 14.987 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 21.934 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324064
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29254 
    [ 2.500,  5.000) = 293144 
    [ 5.000,  7.500) = 1291 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.790 ms/op
     p(99.9900) =     18.232 ms/op
     p(99.9990) =     22.259 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  8.040 ms/op
                 getUser·p0.9999: 17.751 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.810 ms/op
                 getUser·p0.999:  7.141 ms/op
                 getUser·p0.9999: 31.496 ms/op
                 getUser·p1.00:   34.603 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 21.155 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310858
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19370 
    [ 2.500,  5.000) = 289185 
    [ 5.000,  7.500) = 1917 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      7.882 ms/op
     p(99.9900) =     29.652 ms/op
     p(99.9990) =     34.465 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.090 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  14.260 ms/op
                 listUser·p0.9999: 18.815 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.287 ms/op
                 listUser·p0.999:  19.184 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 3.965 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.456 ms/op
                 listUser·p0.9999: 27.918 ms/op
                 listUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237414
  mean =      4.041 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2943 
    [ 2.500,  5.000) = 207888 
    [ 5.000,  7.500) = 24876 
    [ 7.500, 10.000) = 1174 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     17.504 ms/op
     p(99.9900) =     27.271 ms/op
     p(99.9990) =     28.254 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.395 ± 0.449  ops/ms
ClientGrpc.existUser                       thrpt       3  10.766 ± 2.376  ops/ms
ClientGrpc.getUser                         thrpt       3  10.485 ± 2.230  ops/ms
ClientGrpc.listUser                        thrpt       3   7.903 ± 1.861  ops/ms
ClientGrpc.createUser                       avgt       3   3.090 ± 1.242   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.722   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.178   ms/op
ClientGrpc.listUser                         avgt       3   3.901 ± 0.115   ms/op
ClientGrpc.createUser                     sample  310222   3.095 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.940           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  324064   2.962 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.790           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.232           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  310858   3.086 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.882           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.652           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.603           ms/op
ClientGrpc.listUser                       sample  237414   4.041 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.890           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.504           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.271           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.245           ms/op
