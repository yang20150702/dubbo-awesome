# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.039 ops/ms
# Warmup Iteration   2: 2.130 ops/ms
# Warmup Iteration   3: 5.017 ops/ms
Iteration   1: 5.574 ops/ms
Iteration   2: 5.831 ops/ms
Iteration   3: 5.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.757 ±(99.9%) 2.917 ops/ms [Average]
  (min, avg, max) = (5.574, 5.757, 5.866), stdev = 0.160
  CI (99.9%): [2.840, 8.674] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.565 ops/ms
# Warmup Iteration   2: 4.807 ops/ms
# Warmup Iteration   3: 5.863 ops/ms
Iteration   1: 5.941 ops/ms
Iteration   2: 6.119 ops/ms
Iteration   3: 6.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.174 ±(99.9%) 4.820 ops/ms [Average]
  (min, avg, max) = (5.941, 6.174, 6.461), stdev = 0.264
  CI (99.9%): [1.354, 10.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 4.540 ops/ms
# Warmup Iteration   3: 6.015 ops/ms
Iteration   1: 5.855 ops/ms
Iteration   2: 6.022 ops/ms
Iteration   3: 6.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.033 ±(99.9%) 3.343 ops/ms [Average]
  (min, avg, max) = (5.855, 6.033, 6.221), stdev = 0.183
  CI (99.9%): [2.690, 9.376] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 4.360 ops/ms
# Warmup Iteration   3: 5.294 ops/ms
Iteration   1: 4.979 ops/ms
Iteration   2: 5.209 ops/ms
Iteration   3: 5.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.153 ±(99.9%) 2.813 ops/ms [Average]
  (min, avg, max) = (4.979, 5.153, 5.271), stdev = 0.154
  CI (99.9%): [2.340, 7.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.218 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.944 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.823 ±(99.9%) 0.011 ms/op
Iteration   1: 5.429 ±(99.9%) 0.016 ms/op
Iteration   2: 5.382 ±(99.9%) 0.010 ms/op
Iteration   3: 5.360 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.390 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (5.360, 5.390, 5.429), stdev = 0.036
  CI (99.9%): [4.742, 6.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.295 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.276 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.157 ±(99.9%) 0.013 ms/op
Iteration   1: 5.256 ±(99.9%) 0.010 ms/op
Iteration   2: 4.964 ±(99.9%) 0.007 ms/op
Iteration   3: 4.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.064 ±(99.9%) 3.029 ms/op [Average]
  (min, avg, max) = (4.964, 5.064, 5.256), stdev = 0.166
  CI (99.9%): [2.035, 8.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.167 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.358 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.351 ±(99.9%) 0.011 ms/op
Iteration   1: 5.558 ±(99.9%) 0.014 ms/op
Iteration   2: 5.565 ±(99.9%) 0.006 ms/op
Iteration   3: 5.354 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.492 ±(99.9%) 2.186 ms/op [Average]
  (min, avg, max) = (5.354, 5.492, 5.565), stdev = 0.120
  CI (99.9%): [3.307, 7.678] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.271 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 7.553 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.449 ±(99.9%) 0.015 ms/op
Iteration   1: 6.195 ±(99.9%) 0.011 ms/op
Iteration   2: 6.321 ±(99.9%) 0.019 ms/op
Iteration   3: 5.947 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.154 ±(99.9%) 3.479 ms/op [Average]
  (min, avg, max) = (5.947, 6.154, 6.321), stdev = 0.191
  CI (99.9%): [2.676, 9.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.526 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.560 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.993 ±(99.9%) 0.029 ms/op
Iteration   1: 5.252 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.826 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   7.082 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  25.112 ms/op
                 createUser·p0.9999: 29.324 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   2: 5.009 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  24.436 ms/op
                 createUser·p0.9999: 35.118 ms/op
                 createUser·p1.00:   37.028 ms/op

Iteration   3: 5.106 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   9.228 ms/op
                 createUser·p0.999:  26.006 ms/op
                 createUser·p0.9999: 31.767 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187404
  mean =      5.121 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 102158 
    [ 5.000,  7.500) = 79495 
    [ 7.500, 10.000) = 4555 
    [10.000, 12.500) = 615 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     24.759 ms/op
     p(99.9900) =     33.656 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.893 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 5.661 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.729 ±(99.9%) 0.015 ms/op
Iteration   1: 4.737 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.669 ms/op
                 existUser·p0.95:   6.472 ms/op
                 existUser·p0.99:   8.749 ms/op
                 existUser·p0.999:  16.528 ms/op
                 existUser·p0.9999: 29.048 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   2: 4.739 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.249 ms/op
                 existUser·p0.50:   4.448 ms/op
                 existUser·p0.90:   5.980 ms/op
                 existUser·p0.95:   6.996 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  13.139 ms/op
                 existUser·p0.9999: 28.106 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 4.745 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   4.506 ms/op
                 existUser·p0.90:   5.636 ms/op
                 existUser·p0.95:   6.300 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  18.861 ms/op
                 existUser·p0.9999: 31.588 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 202517
  mean =      4.740 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 153389 
    [ 5.000,  7.500) = 43586 
    [ 7.500, 10.000) = 4187 
    [10.000, 12.500) = 803 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.603 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     18.020 ms/op
     p(99.9900) =     30.499 ms/op
     p(99.9990) =     32.078 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.939 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 5.962 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.403 ±(99.9%) 0.019 ms/op
Iteration   1: 5.351 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.449 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.569 ms/op
                 getUser·p0.99:   10.469 ms/op
                 getUser·p0.999:  25.132 ms/op
                 getUser·p0.9999: 33.064 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   2: 5.260 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.494 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.545 ms/op
                 getUser·p0.99:   10.734 ms/op
                 getUser·p0.999:  28.089 ms/op
                 getUser·p0.9999: 32.402 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   3: 5.010 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.564 ms/op
                 getUser·p0.50:   4.841 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  28.270 ms/op
                 getUser·p0.9999: 32.637 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184300
  mean =      5.203 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 99379 
    [ 5.000,  7.500) = 77211 
    [ 7.500, 10.000) = 5720 
    [10.000, 12.500) = 1111 
    [12.500, 15.000) = 472 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 79 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.449 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.193 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     25.493 ms/op
     p(99.9900) =     32.791 ms/op
     p(99.9990) =     34.417 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.070 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.381 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.424 ±(99.9%) 0.026 ms/op
Iteration   1: 6.564 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   13.238 ms/op
                 listUser·p0.999:  27.833 ms/op
                 listUser·p0.9999: 33.552 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   2: 6.580 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.568 ms/op
                 listUser·p0.99:   12.998 ms/op
                 listUser·p0.999:  31.020 ms/op
                 listUser·p0.9999: 37.434 ms/op
                 listUser·p1.00:   39.125 ms/op

Iteration   3: 6.158 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.580 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  22.578 ms/op
                 listUser·p0.9999: 33.509 ms/op
                 listUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149433
  mean =      6.428 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 8221 
    [ 5.000,  7.500) = 119948 
    [ 7.500, 10.000) = 15982 
    [10.000, 12.500) = 3686 
    [12.500, 15.000) = 934 
    [15.000, 17.500) = 275 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      8.045 ms/op
     p(95.0000) =      9.306 ms/op
     p(99.0000) =     12.616 ms/op
     p(99.9000) =     27.970 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     39.093 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.757 ± 2.917  ops/ms
ClientPb.existUser                       thrpt       3   6.174 ± 4.820  ops/ms
ClientPb.getUser                         thrpt       3   6.033 ± 3.343  ops/ms
ClientPb.listUser                        thrpt       3   5.153 ± 2.813  ops/ms
ClientPb.createUser                       avgt       3   5.390 ± 0.648   ms/op
ClientPb.existUser                        avgt       3   5.064 ± 3.029   ms/op
ClientPb.getUser                          avgt       3   5.492 ± 2.186   ms/op
ClientPb.listUser                         avgt       3   6.154 ± 3.479   ms/op
ClientPb.createUser                     sample  187404   5.121 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.840           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.175           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.759           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.656           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  202517   4.740 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.485           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.077           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.020           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.499           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  184300   5.203 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.449           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.158           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.493           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.791           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  149433   6.428 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.616           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.970           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.125           ms/op
