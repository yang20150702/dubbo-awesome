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
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 6.556 ops/ms
# Warmup Iteration   3: 7.517 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.080 ops/ms
Iteration   3: 8.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.068 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (8.038, 8.068, 8.085), stdev = 0.026
  CI (99.9%): [7.591, 8.545] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.185 ops/ms
# Warmup Iteration   2: 7.869 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 8.739 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.687 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (8.551, 8.687, 8.772), stdev = 0.120
  CI (99.9%): [6.507, 10.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 7.346 ops/ms
# Warmup Iteration   3: 7.969 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.974 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (7.906, 7.974, 8.081), stdev = 0.094
  CI (99.9%): [6.267, 9.681] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.229 ops/ms
# Warmup Iteration   2: 5.641 ops/ms
# Warmup Iteration   3: 6.241 ops/ms
Iteration   1: 6.227 ops/ms
Iteration   2: 6.470 ops/ms
Iteration   3: 6.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.351 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (6.227, 6.351, 6.470), stdev = 0.121
  CI (99.9%): [4.136, 8.567] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.703 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.005 ms/op
Iteration   1: 4.162 ±(99.9%) 0.003 ms/op
Iteration   2: 4.053 ±(99.9%) 0.002 ms/op
Iteration   3: 3.825 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.013 ±(99.9%) 3.142 ms/op [Average]
  (min, avg, max) = (3.825, 4.013, 4.162), stdev = 0.172
  CI (99.9%): [0.871, 7.155] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.326 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.007 ms/op
Iteration   1: 3.655 ±(99.9%) 0.003 ms/op
Iteration   2: 3.699 ±(99.9%) 0.003 ms/op
Iteration   3: 3.823 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.725 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (3.655, 3.725, 3.823), stdev = 0.087
  CI (99.9%): [2.139, 5.312] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.511 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.007 ms/op
Iteration   1: 4.150 ±(99.9%) 0.003 ms/op
Iteration   2: 4.043 ±(99.9%) 0.005 ms/op
Iteration   3: 4.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.100 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (4.043, 4.100, 4.150), stdev = 0.054
  CI (99.9%): [3.115, 5.085] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.484 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.542 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.019 ms/op
Iteration   1: 5.054 ±(99.9%) 0.019 ms/op
Iteration   2: 5.111 ±(99.9%) 0.011 ms/op
Iteration   3: 5.127 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.097 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (5.054, 5.097, 5.127), stdev = 0.039
  CI (99.9%): [4.394, 5.801] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.278 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.012 ms/op
Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  14.879 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.994 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   7.131 ms/op
                 createUser·p0.999:  14.336 ms/op
                 createUser·p0.9999: 21.528 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.911 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  12.074 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 241542
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6168 
    [ 2.500,  5.000) = 211404 
    [ 5.000,  7.500) = 21831 
    [ 7.500, 10.000) = 1263 
    [10.000, 12.500) = 452 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      7.230 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     20.732 ms/op
     p(99.9990) =     23.323 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.718 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.010 ms/op
Iteration   1: 3.734 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  9.080 ms/op
                 existUser·p0.9999: 19.314 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 3.718 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  12.631 ms/op
                 existUser·p0.9999: 18.376 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   3: 3.704 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  8.385 ms/op
                 existUser·p0.9999: 21.135 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 258247
  mean =      3.719 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7165 
    [ 2.500,  5.000) = 235199 
    [ 5.000,  7.500) = 14732 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.566 ms/op
     p(99.9000) =     11.039 ms/op
     p(99.9900) =     19.449 ms/op
     p(99.9990) =     21.444 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.728 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.012 ms/op
Iteration   1: 3.996 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.945 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  11.451 ms/op
                 getUser·p0.9999: 21.165 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  9.198 ms/op
                 getUser·p0.9999: 23.010 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240394
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4588 
    [ 2.500,  5.000) = 211534 
    [ 5.000,  7.500) = 22787 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     21.493 ms/op
     p(99.9990) =     23.448 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 7.332 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.513 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.054 ±(99.9%) 0.017 ms/op
Iteration   1: 5.175 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 5.243 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.996 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   10.741 ms/op
                 listUser·p0.999:  18.115 ms/op
                 listUser·p0.9999: 29.376 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 5.144 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   9.558 ms/op
                 listUser·p0.999:  21.753 ms/op
                 listUser·p0.9999: 26.848 ms/op
                 listUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184957
  mean =      5.187 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 208 
    [ 2.500,  5.000) = 99713 
    [ 5.000,  7.500) = 73895 
    [ 7.500, 10.000) = 9243 
    [10.000, 12.500) = 1233 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     27.083 ms/op
     p(99.9990) =     35.606 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.068 ± 0.477  ops/ms
ClientGrpc.existUser                       thrpt       3   8.687 ± 2.181  ops/ms
ClientGrpc.getUser                         thrpt       3   7.974 ± 1.707  ops/ms
ClientGrpc.listUser                        thrpt       3   6.351 ± 2.216  ops/ms
ClientGrpc.createUser                       avgt       3   4.013 ± 3.142   ms/op
ClientGrpc.existUser                        avgt       3   3.725 ± 1.587   ms/op
ClientGrpc.getUser                          avgt       3   4.100 ± 0.985   ms/op
ClientGrpc.listUser                         avgt       3   5.097 ± 0.704   ms/op
ClientGrpc.createUser                     sample  241542   3.972 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.851           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.230           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.205           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.732           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  258247   3.719 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.657           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.566           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.039           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.449           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  240394   3.993 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.994           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.840           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.125           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.493           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  184957   5.187 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.984           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.741           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.448           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.083           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.717           ms/op
