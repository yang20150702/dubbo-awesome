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
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 8.885 ops/ms
# Warmup Iteration   3: 9.807 ops/ms
Iteration   1: 10.304 ops/ms
Iteration   2: 10.209 ops/ms
Iteration   3: 10.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.269 ±(99.9%) 0.953 ops/ms [Average]
  (min, avg, max) = (10.209, 10.269, 10.304), stdev = 0.052
  CI (99.9%): [9.316, 11.223] (assumes normal distribution)


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
# Warmup Iteration   1: 7.098 ops/ms
# Warmup Iteration   2: 10.280 ops/ms
# Warmup Iteration   3: 10.951 ops/ms
Iteration   1: 11.055 ops/ms
Iteration   2: 10.987 ops/ms
Iteration   3: 11.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.120 ±(99.9%) 3.178 ops/ms [Average]
  (min, avg, max) = (10.987, 11.120, 11.317), stdev = 0.174
  CI (99.9%): [7.942, 14.298] (assumes normal distribution)


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
# Warmup Iteration   1: 6.898 ops/ms
# Warmup Iteration   2: 9.904 ops/ms
# Warmup Iteration   3: 10.342 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.479 ops/ms
Iteration   3: 10.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.397 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (10.351, 10.397, 10.479), stdev = 0.071
  CI (99.9%): [9.099, 11.695] (assumes normal distribution)


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
# Warmup Iteration   1: 6.147 ops/ms
# Warmup Iteration   2: 7.910 ops/ms
# Warmup Iteration   3: 7.874 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 7.817 ops/ms
Iteration   3: 7.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.816 ±(99.9%) 0.118 ops/ms [Average]
  (min, avg, max) = (7.809, 7.816, 7.822), stdev = 0.006
  CI (99.9%): [7.698, 7.934] (assumes normal distribution)


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 3.141 ±(99.9%) 0.004 ms/op
Iteration   2: 3.088 ±(99.9%) 0.002 ms/op
Iteration   3: 3.151 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.127 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.088, 3.127, 3.151), stdev = 0.034
  CI (99.9%): [2.512, 3.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.878 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.002 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (2.878, 2.930, 2.956), stdev = 0.044
  CI (99.9%): [2.121, 3.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.003 ms/op
Iteration   1: 3.096 ±(99.9%) 0.003 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.041, 3.074, 3.096), stdev = 0.029
  CI (99.9%): [2.538, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 5.652 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.015 ms/op
Iteration   1: 4.008 ±(99.9%) 0.021 ms/op
Iteration   2: 4.046 ±(99.9%) 0.009 ms/op
Iteration   3: 4.072 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.042 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (4.008, 4.042, 4.072), stdev = 0.032
  CI (99.9%): [3.453, 4.631] (assumes normal distribution)


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  8.886 ms/op
                 createUser·p0.9999: 13.180 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.929 ms/op
                 createUser·p0.9999: 14.696 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.608 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312432
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 703 
    [ 1.250,  2.500) = 21760 
    [ 2.500,  3.750) = 267452 
    [ 3.750,  5.000) = 20354 
    [ 5.000,  6.250) = 1135 
    [ 6.250,  7.500) = 470 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.661 ms/op
     p(99.9000) =      8.800 ms/op
     p(99.9900) =     16.241 ms/op
     p(99.9990) =     16.775 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.522 ms/op
                 existUser·p0.9999: 13.271 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  8.020 ms/op
                 existUser·p0.9999: 17.406 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 2.940 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.711 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326575
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33296 
    [ 2.500,  5.000) = 291217 
    [ 5.000,  7.500) = 1646 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     17.280 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.680 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.386 ms/op
                 getUser·p0.9999: 18.670 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  8.723 ms/op
                 getUser·p0.9999: 29.171 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.971 ms/op
                 getUser·p0.9999: 23.763 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310134
  mean =      3.094 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16428 
    [ 2.500,  5.000) = 291372 
    [ 5.000,  7.500) = 1790 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     28.376 ms/op
     p(99.9990) =     29.452 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.012 ms/op
Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.993 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.618 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 27.721 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   3: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 18.329 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236882
  mean =      4.056 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1770 
    [ 2.500,  5.000) = 207296 
    [ 5.000,  7.500) = 25670 
    [ 7.500, 10.000) = 1570 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     14.682 ms/op
     p(99.9900) =     27.283 ms/op
     p(99.9990) =     28.648 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.269 ± 0.953  ops/ms
ClientGrpc.existUser                       thrpt       3  11.120 ± 3.178  ops/ms
ClientGrpc.getUser                         thrpt       3  10.397 ± 1.298  ops/ms
ClientGrpc.listUser                        thrpt       3   7.816 ± 0.118  ops/ms
ClientGrpc.createUser                       avgt       3   3.127 ± 0.614   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.809   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 0.536   ms/op
ClientGrpc.listUser                         avgt       3   4.042 ± 0.589   ms/op
ClientGrpc.createUser                     sample  312432   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.800           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.241           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.138           ms/op
ClientGrpc.existUser                      sample  326575   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.614           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.741           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.280           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  310134   3.094 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.760           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.618           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.376           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.147           ms/op
ClientGrpc.listUser                       sample  236882   4.056 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.618           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.682           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.283           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.770           ms/op
