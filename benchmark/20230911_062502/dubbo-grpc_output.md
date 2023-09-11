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
# Warmup Iteration   1: 3.087 ops/ms
# Warmup Iteration   2: 6.922 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.294 ops/ms
Iteration   3: 8.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.478 ±(99.9%) 4.063 ops/ms [Average]
  (min, avg, max) = (8.294, 8.478, 8.726), stdev = 0.223
  CI (99.9%): [4.416, 12.541] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.264 ops/ms
# Warmup Iteration   2: 8.414 ops/ms
# Warmup Iteration   3: 8.767 ops/ms
Iteration   1: 9.061 ops/ms
Iteration   2: 8.966 ops/ms
Iteration   3: 8.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.987 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (8.935, 8.987, 9.061), stdev = 0.066
  CI (99.9%): [7.785, 10.190] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.784 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.433 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.466 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (8.433, 8.466, 8.507), stdev = 0.038
  CI (99.9%): [7.774, 9.158] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 5.837 ops/ms
# Warmup Iteration   3: 6.291 ops/ms
Iteration   1: 6.345 ops/ms
Iteration   2: 6.635 ops/ms
Iteration   3: 6.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.503 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (6.345, 6.503, 6.635), stdev = 0.147
  CI (99.9%): [3.824, 9.182] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.346 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.005 ms/op
Iteration   1: 3.852 ±(99.9%) 0.003 ms/op
Iteration   2: 3.783 ±(99.9%) 0.004 ms/op
Iteration   3: 3.774 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.803 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.774, 3.803, 3.852), stdev = 0.043
  CI (99.9%): [3.021, 4.585] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.006 ms/op
Iteration   1: 3.626 ±(99.9%) 0.003 ms/op
Iteration   2: 3.536 ±(99.9%) 0.004 ms/op
Iteration   3: 3.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.566 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.536, 3.566, 3.626), stdev = 0.052
  CI (99.9%): [2.615, 4.517] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.003 ms/op
Iteration   1: 3.836 ±(99.9%) 0.004 ms/op
Iteration   2: 3.699 ±(99.9%) 0.004 ms/op
Iteration   3: 3.716 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.750 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (3.699, 3.750, 3.836), stdev = 0.075
  CI (99.9%): [2.389, 5.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.723 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.200 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.016 ms/op
Iteration   1: 4.807 ±(99.9%) 0.009 ms/op
Iteration   2: 4.996 ±(99.9%) 0.010 ms/op
Iteration   3: 4.945 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.916 ±(99.9%) 1.779 ms/op [Average]
  (min, avg, max) = (4.807, 4.916, 4.996), stdev = 0.098
  CI (99.9%): [3.137, 6.695] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.011 ms/op
Iteration   1: 3.655 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 18.989 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   2: 3.826 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  9.467 ms/op
                 createUser·p0.9999: 19.092 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   3: 3.757 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  13.101 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256198
  mean =      3.745 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6828 
    [ 2.500,  5.000) = 236896 
    [ 5.000,  7.500) = 11067 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     24.626 ms/op
     p(99.9990) =     26.665 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.008 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.011 ms/op
Iteration   1: 3.595 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  10.274 ms/op
                 existUser·p0.9999: 19.930 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.580 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 17.896 ms/op
                 existUser·p1.00:   18.612 ms/op

Iteration   3: 3.527 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  9.574 ms/op
                 existUser·p0.9999: 18.086 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268947
  mean =      3.567 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15035 
    [ 2.500,  5.000) = 244134 
    [ 5.000,  7.500) = 8596 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.238 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.778 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 5.585 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.010 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  12.819 ms/op
                 getUser·p0.9999: 14.684 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 3.874 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  12.619 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 22.426 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251250
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9783 
    [ 2.500,  5.000) = 225610 
    [ 5.000,  7.500) = 14355 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.916 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     24.673 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 6.694 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.764 ±(99.9%) 0.015 ms/op
Iteration   1: 4.900 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.332 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  16.614 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 4.985 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  21.884 ms/op
                 listUser·p0.9999: 28.028 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   3: 5.039 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  24.445 ms/op
                 listUser·p0.9999: 32.930 ms/op
                 listUser·p1.00:   42.402 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192936
  mean =      4.974 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 128756 
    [ 5.000, 10.000) = 62406 
    [10.000, 15.000) = 1334 
    [15.000, 20.000) = 228 
    [20.000, 25.000) = 104 
    [25.000, 30.000) = 77 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.440 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     21.725 ms/op
     p(99.9900) =     32.356 ms/op
     p(99.9990) =     40.392 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.478 ± 4.063  ops/ms
ClientGrpc.existUser                       thrpt       3   8.987 ± 1.202  ops/ms
ClientGrpc.getUser                         thrpt       3   8.466 ± 0.692  ops/ms
ClientGrpc.listUser                        thrpt       3   6.503 ± 2.679  ops/ms
ClientGrpc.createUser                       avgt       3   3.803 ± 0.782   ms/op
ClientGrpc.existUser                        avgt       3   3.566 ± 0.951   ms/op
ClientGrpc.getUser                          avgt       3   3.750 ± 1.361   ms/op
ClientGrpc.listUser                         avgt       3   4.916 ± 1.779   ms/op
ClientGrpc.createUser                     sample  256198   3.745 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.765           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.435           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.739           ms/op
ClientGrpc.existUser                      sample  268947   3.567 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.881           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.776           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.238           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.732           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.366           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.922           ms/op
ClientGrpc.getUser                        sample  251250   3.820 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.840           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.742           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.916           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.414           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.773           ms/op
ClientGrpc.listUser                       sample  192936   4.974 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.488           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.440           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.725           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.356           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          42.402           ms/op
