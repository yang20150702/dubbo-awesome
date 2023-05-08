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
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 9.202 ops/ms
# Warmup Iteration   3: 10.159 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.552 ±(99.9%) 0.857 ops/ms [Average]
  (min, avg, max) = (10.500, 10.552, 10.592), stdev = 0.047
  CI (99.9%): [9.695, 11.409] (assumes normal distribution)


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
# Warmup Iteration   1: 7.666 ops/ms
# Warmup Iteration   2: 10.605 ops/ms
# Warmup Iteration   3: 11.048 ops/ms
Iteration   1: 10.897 ops/ms
Iteration   2: 11.050 ops/ms
Iteration   3: 11.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.987 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (10.897, 10.987, 11.050), stdev = 0.080
  CI (99.9%): [9.529, 12.445] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.631 ops/ms
# Warmup Iteration   2: 10.082 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.623 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.574 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (10.467, 10.574, 10.631), stdev = 0.093
  CI (99.9%): [8.880, 12.268] (assumes normal distribution)


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
# Warmup Iteration   1: 6.527 ops/ms
# Warmup Iteration   2: 7.306 ops/ms
# Warmup Iteration   3: 7.978 ops/ms
Iteration   1: 7.969 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.996 ±(99.9%) 0.772 ops/ms [Average]
  (min, avg, max) = (7.969, 7.996, 8.045), stdev = 0.042
  CI (99.9%): [7.224, 8.768] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.002 ms/op
Iteration   1: 3.064 ±(99.9%) 0.004 ms/op
Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
Iteration   3: 3.032 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.032, 3.056, 3.072), stdev = 0.022
  CI (99.9%): [2.663, 3.449] (assumes normal distribution)


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.003 ms/op
Iteration   1: 2.867 ±(99.9%) 0.002 ms/op
Iteration   2: 2.911 ±(99.9%) 0.001 ms/op
Iteration   3: 2.897 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.867, 2.892, 2.911), stdev = 0.022
  CI (99.9%): [2.486, 3.297] (assumes normal distribution)


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.003 ms/op
Iteration   2: 3.058 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.016, 3.062, 3.113), stdev = 0.049
  CI (99.9%): [2.168, 3.957] (assumes normal distribution)


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
# Warmup Iteration   1: 5.696 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.024 ms/op
Iteration   1: 3.929 ±(99.9%) 0.021 ms/op
Iteration   2: 3.943 ±(99.9%) 0.011 ms/op
Iteration   3: 3.966 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.929, 3.946, 3.966), stdev = 0.019
  CI (99.9%): [3.605, 4.287] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 14.818 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  10.397 ms/op
                 createUser·p0.9999: 15.643 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.435 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.338 ms/op
                 createUser·p0.999:  6.652 ms/op
                 createUser·p0.9999: 17.999 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318038
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 388 
    [ 1.250,  2.500) = 16722 
    [ 2.500,  3.750) = 286875 
    [ 3.750,  5.000) = 12447 
    [ 5.000,  6.250) = 858 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      9.125 ms/op
     p(99.9900) =     17.347 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
Iteration   1: 2.939 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.009 ms/op

Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  8.135 ms/op
                 existUser·p0.9999: 12.378 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.330 ms/op
                 existUser·p0.9999: 15.419 ms/op
                 existUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327263
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 326 
    [ 1.250,  2.500) = 27058 
    [ 2.500,  3.750) = 292791 
    [ 3.750,  5.000) = 5586 
    [ 5.000,  6.250) = 723 
    [ 6.250,  7.500) = 427 
    [ 7.500,  8.750) = 125 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      7.663 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     15.949 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.462 ms/op
                 getUser·p0.999:  7.659 ms/op
                 getUser·p0.9999: 15.934 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.289 ms/op
                 getUser·p0.999:  6.275 ms/op
                 getUser·p0.9999: 17.099 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315344
  mean =      3.044 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 804 
    [ 1.250,  2.500) = 20475 
    [ 2.500,  3.750) = 274633 
    [ 3.750,  5.000) = 18057 
    [ 5.000,  6.250) = 890 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     15.933 ms/op
     p(99.9990) =     17.483 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
Iteration   1: 3.946 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 26.460 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 3.986 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.503 ms/op
                 listUser·p0.9999: 17.956 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.080 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 23.434 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240556
  mean =      3.990 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2392 
    [ 2.500,  5.000) = 214589 
    [ 5.000,  7.500) = 22163 
    [ 7.500, 10.000) = 930 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.359 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     26.725 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.552 ± 0.857  ops/ms
ClientGrpc.existUser                       thrpt       3  10.987 ± 1.458  ops/ms
ClientGrpc.getUser                         thrpt       3  10.574 ± 1.694  ops/ms
ClientGrpc.listUser                        thrpt       3   7.996 ± 0.772  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 0.393   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.405   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.895   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.341   ms/op
ClientGrpc.createUser                     sample  318038   3.018 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.435           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.125           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.347           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.235           ms/op
ClientGrpc.existUser                      sample  327263   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.801           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.663           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.680           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.089           ms/op
ClientGrpc.getUser                        sample  315344   3.044 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.601           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.933           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.596           ms/op
ClientGrpc.listUser                       sample  240556   3.990 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.860           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.359           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.379           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
