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
# Warmup Iteration   1: 3.814 ops/ms
# Warmup Iteration   2: 8.446 ops/ms
# Warmup Iteration   3: 9.804 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 9.930 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.154 ±(99.9%) 3.845 ops/ms [Average]
  (min, avg, max) = (9.930, 10.154, 10.348), stdev = 0.211
  CI (99.9%): [6.309, 13.999] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.792 ops/ms
# Warmup Iteration   2: 10.037 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 11.105 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.805 ±(99.9%) 4.773 ops/ms [Average]
  (min, avg, max) = (10.627, 10.805, 11.105), stdev = 0.262
  CI (99.9%): [6.032, 15.578] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.686 ops/ms
# Warmup Iteration   2: 9.736 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 10.168 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.221 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (10.168, 10.221, 10.313), stdev = 0.079
  CI (99.9%): [8.772, 11.671] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.243 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 7.732 ops/ms
Iteration   1: 7.717 ops/ms
Iteration   2: 7.910 ops/ms
Iteration   3: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.812 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (7.717, 7.812, 7.910), stdev = 0.097
  CI (99.9%): [6.050, 9.575] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.002 ms/op
Iteration   1: 3.151 ±(99.9%) 0.001 ms/op
Iteration   2: 3.078 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.131 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.078, 3.131, 3.163), stdev = 0.046
  CI (99.9%): [2.291, 3.970] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 2.959 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.005 ±(99.9%) 1.140 ms/op [Average]
  (min, avg, max) = (2.959, 3.005, 3.076), stdev = 0.062
  CI (99.9%): [1.866, 4.145] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.003 ms/op
Iteration   1: 3.191 ±(99.9%) 0.002 ms/op
Iteration   2: 3.098 ±(99.9%) 0.001 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.157 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.098, 3.157, 3.191), stdev = 0.051
  CI (99.9%): [2.222, 4.091] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.891 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.024 ms/op
Iteration   1: 4.021 ±(99.9%) 0.007 ms/op
Iteration   2: 3.930 ±(99.9%) 0.030 ms/op
Iteration   3: 3.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.979 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.930, 3.979, 4.021), stdev = 0.046
  CI (99.9%): [3.147, 4.811] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.228 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.462 ms/op
                 createUser·p0.9999: 17.239 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.185 ms/op
                 createUser·p0.9999: 17.861 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.334 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.312 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298359
  mean =      3.216 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21898 
    [ 2.500,  5.000) = 275425 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.369 ms/op
     p(99.9900) =     21.239 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.079 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.211 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.626 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.514 ms/op
                 existUser·p0.9999: 16.587 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312644
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 798 
    [ 1.250,  2.500) = 38622 
    [ 2.500,  3.750) = 242507 
    [ 3.750,  5.000) = 29737 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.352 ms/op
     p(99.9900) =     18.479 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.042 ms/op
                 getUser·p0.9999: 24.376 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  8.708 ms/op
                 getUser·p0.9999: 19.232 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.209 ms/op
                 getUser·p0.9999: 36.113 ms/op
                 getUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300864
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23915 
    [ 2.500,  5.000) = 275776 
    [ 5.000,  7.500) = 798 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.382 ms/op
     p(99.9900) =     34.859 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 5.289 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.011 ms/op
Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  16.038 ms/op
                 listUser·p0.9999: 20.251 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.117 ms/op
                 listUser·p0.999:  14.857 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.045 ms/op
                 listUser·p0.9999: 21.656 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240146
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1415 
    [ 2.500,  5.000) = 214414 
    [ 5.000,  7.500) = 22887 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.000 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     20.086 ms/op
     p(99.9990) =     22.236 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.154 ± 3.845  ops/ms
ClientGrpc.existUser                       thrpt       3  10.805 ± 4.773  ops/ms
ClientGrpc.getUser                         thrpt       3  10.221 ± 1.449  ops/ms
ClientGrpc.listUser                        thrpt       3   7.812 ± 1.763  ops/ms
ClientGrpc.createUser                       avgt       3   3.131 ± 0.839   ms/op
ClientGrpc.existUser                        avgt       3   3.005 ± 1.140   ms/op
ClientGrpc.getUser                          avgt       3   3.157 ± 0.935   ms/op
ClientGrpc.listUser                         avgt       3   3.979 ± 0.832   ms/op
ClientGrpc.createUser                     sample  298359   3.216 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.334           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.096           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.369           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.239           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.315           ms/op
ClientGrpc.existUser                      sample  312644   3.069 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.740           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.352           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.479           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  300864   3.187 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.662           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.039           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.382           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.859           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.569           ms/op
ClientGrpc.listUser                       sample  240146   3.998 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.987           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.000           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.086           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
