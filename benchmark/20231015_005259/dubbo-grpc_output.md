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
# Warmup Iteration   1: 3.842 ops/ms
# Warmup Iteration   2: 8.187 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 9.829 ops/ms
Iteration   2: 9.911 ops/ms
Iteration   3: 9.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.862 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (9.829, 9.862, 9.911), stdev = 0.044
  CI (99.9%): [9.061, 10.662] (assumes normal distribution)


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
# Warmup Iteration   1: 6.942 ops/ms
# Warmup Iteration   2: 9.852 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.673 ops/ms
Iteration   2: 10.566 ops/ms
Iteration   3: 10.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.543 ±(99.9%) 2.598 ops/ms [Average]
  (min, avg, max) = (10.391, 10.543, 10.673), stdev = 0.142
  CI (99.9%): [7.946, 13.141] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.697 ops/ms
# Warmup Iteration   2: 9.572 ops/ms
# Warmup Iteration   3: 9.891 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.015 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (9.944, 10.015, 10.066), stdev = 0.064
  CI (99.9%): [8.850, 11.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.942 ops/ms
# Warmup Iteration   2: 7.726 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 7.878 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 8.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (7.878, 7.985, 8.051), stdev = 0.093
  CI (99.9%): [6.286, 9.684] (assumes normal distribution)


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.003 ms/op
Iteration   1: 3.162 ±(99.9%) 0.003 ms/op
Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
Iteration   3: 3.229 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.213 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.162, 3.213, 3.247), stdev = 0.044
  CI (99.9%): [2.402, 4.024] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.003 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (2.964, 3.003, 3.061), stdev = 0.051
  CI (99.9%): [2.077, 3.929] (assumes normal distribution)


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
# Warmup Iteration   1: 4.615 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.004 ms/op
Iteration   1: 3.252 ±(99.9%) 0.003 ms/op
Iteration   2: 3.148 ±(99.9%) 0.003 ms/op
Iteration   3: 3.132 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.178 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.132, 3.178, 3.252), stdev = 0.065
  CI (99.9%): [1.992, 4.363] (assumes normal distribution)


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
# Warmup Iteration   1: 5.972 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.031 ms/op
Iteration   1: 3.986 ±(99.9%) 0.051 ms/op
Iteration   2: 3.999 ±(99.9%) 0.019 ms/op
Iteration   3: 4.040 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.008 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.986, 4.008, 4.040), stdev = 0.029
  CI (99.9%): [3.487, 4.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.007 ms/op
Iteration   1: 3.166 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.683 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   17.826 ms/op

Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 20.218 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301443
  mean =      3.184 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9010 
    [ 2.500,  5.000) = 290665 
    [ 5.000,  7.500) = 1314 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.898 ms/op
                 existUser·p0.9999: 15.800 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.736 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.050 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.857 ms/op
                 existUser·p0.9999: 17.187 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314785
  mean =      3.048 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15914 
    [ 2.500,  5.000) = 297339 
    [ 5.000,  7.500) = 1162 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.989 ms/op
     p(99.9900) =     17.860 ms/op
     p(99.9990) =     24.173 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.008 ms/op
Iteration   1: 3.261 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 18.001 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  12.524 ms/op
                 getUser·p0.9999: 19.664 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.284 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  14.945 ms/op
                 getUser·p0.9999: 26.932 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 297648
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8221 
    [ 2.500,  5.000) = 286987 
    [ 5.000,  7.500) = 1718 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =     12.212 ms/op
     p(99.9900) =     25.731 ms/op
     p(99.9990) =     27.854 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 5.825 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.013 ms/op
Iteration   1: 4.019 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.080 ms/op
                 listUser·p0.999:  22.708 ms/op
                 listUser·p0.9999: 27.528 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   2: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.247 ms/op
                 listUser·p0.9999: 28.545 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   3: 3.995 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238974
  mean =      4.015 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2582 
    [ 2.500,  5.000) = 219264 
    [ 5.000,  7.500) = 15558 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     18.352 ms/op
     p(99.9900) =     27.532 ms/op
     p(99.9990) =     29.551 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.862 ± 0.800  ops/ms
ClientGrpc.existUser                       thrpt       3  10.543 ± 2.598  ops/ms
ClientGrpc.getUser                         thrpt       3  10.015 ± 1.165  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 1.699  ops/ms
ClientGrpc.createUser                       avgt       3   3.213 ± 0.811   ms/op
ClientGrpc.existUser                        avgt       3   3.003 ± 0.926   ms/op
ClientGrpc.getUser                          avgt       3   3.178 ± 1.186   ms/op
ClientGrpc.listUser                         avgt       3   4.008 ± 0.521   ms/op
ClientGrpc.createUser                     sample  301443   3.184 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.648           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.142           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.218           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  314785   3.048 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.989           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.860           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.314           ms/op
ClientGrpc.getUser                        sample  297648   3.226 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.284           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.212           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.731           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.017           ms/op
ClientGrpc.listUser                       sample  238974   4.015 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.852           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.532           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
