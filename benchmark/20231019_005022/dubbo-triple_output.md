# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.040 ops/ms
# Warmup Iteration   2: 2.369 ops/ms
# Warmup Iteration   3: 5.583 ops/ms
Iteration   1: 5.828 ops/ms
Iteration   2: 5.915 ops/ms
Iteration   3: 6.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.975 ±(99.9%) 3.345 ops/ms [Average]
  (min, avg, max) = (5.828, 5.975, 6.180), stdev = 0.183
  CI (99.9%): [2.630, 9.319] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.761 ops/ms
# Warmup Iteration   2: 5.143 ops/ms
# Warmup Iteration   3: 6.204 ops/ms
Iteration   1: 6.561 ops/ms
Iteration   2: 6.499 ops/ms
Iteration   3: 6.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.520 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (6.499, 6.520, 6.561), stdev = 0.036
  CI (99.9%): [5.867, 7.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.646 ops/ms
# Warmup Iteration   2: 4.612 ops/ms
# Warmup Iteration   3: 5.911 ops/ms
Iteration   1: 6.144 ops/ms
Iteration   2: 5.949 ops/ms
Iteration   3: 6.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.074 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (5.949, 6.074, 6.144), stdev = 0.108
  CI (99.9%): [4.096, 8.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 3.888 ops/ms
# Warmup Iteration   3: 5.254 ops/ms
Iteration   1: 5.227 ops/ms
Iteration   2: 5.095 ops/ms
Iteration   3: 5.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.175 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (5.095, 5.175, 5.227), stdev = 0.070
  CI (99.9%): [3.896, 6.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.566 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.630 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.012 ms/op
Iteration   1: 5.222 ±(99.9%) 0.015 ms/op
Iteration   2: 5.323 ±(99.9%) 0.016 ms/op
Iteration   3: 5.271 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.272 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (5.222, 5.272, 5.323), stdev = 0.051
  CI (99.9%): [4.350, 6.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.120 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.029 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.006 ms/op
Iteration   1: 5.231 ±(99.9%) 0.004 ms/op
Iteration   2: 5.193 ±(99.9%) 0.008 ms/op
Iteration   3: 5.003 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.142 ±(99.9%) 2.223 ms/op [Average]
  (min, avg, max) = (5.003, 5.142, 5.231), stdev = 0.122
  CI (99.9%): [2.919, 7.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.461 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.733 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.467 ±(99.9%) 0.013 ms/op
Iteration   1: 5.574 ±(99.9%) 0.014 ms/op
Iteration   2: 5.412 ±(99.9%) 0.011 ms/op
Iteration   3: 5.336 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.441 ±(99.9%) 2.222 ms/op [Average]
  (min, avg, max) = (5.336, 5.441, 5.574), stdev = 0.122
  CI (99.9%): [3.218, 7.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.676 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.225 ±(99.9%) 0.009 ms/op
Iteration   1: 5.986 ±(99.9%) 0.011 ms/op
Iteration   2: 5.917 ±(99.9%) 0.016 ms/op
Iteration   3: 6.130 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.011 ±(99.9%) 1.982 ms/op [Average]
  (min, avg, max) = (5.917, 6.011, 6.130), stdev = 0.109
  CI (99.9%): [4.029, 7.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.463 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 6.484 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.803 ±(99.9%) 0.027 ms/op
Iteration   1: 5.205 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   7.242 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 26.500 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 5.077 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.036 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.029 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  24.773 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 5.350 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  27.172 ms/op
                 createUser·p0.9999: 31.494 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184222
  mean =      5.209 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 98014 
    [ 5.000,  7.500) = 79329 
    [ 7.500, 10.000) = 5384 
    [10.000, 12.500) = 787 
    [12.500, 15.000) = 371 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.135 ms/op
     p(99.0000) =      9.417 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     31.987 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.948 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 5.957 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.210 ±(99.9%) 0.020 ms/op
Iteration   1: 5.065 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  23.260 ms/op
                 existUser·p0.9999: 27.221 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 5.203 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.032 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.390 ms/op
                 existUser·p0.95:   7.725 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  21.955 ms/op
                 existUser·p0.9999: 26.565 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   3: 5.068 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.503 ms/op
                 existUser·p0.999:  25.228 ms/op
                 existUser·p0.9999: 35.501 ms/op
                 existUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187701
  mean =      5.111 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 111060 
    [ 5.000,  7.500) = 68730 
    [ 7.500, 10.000) = 6156 
    [10.000, 12.500) = 1246 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     22.040 ms/op
     p(99.9900) =     33.312 ms/op
     p(99.9990) =     35.941 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.449 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.408 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.567 ±(99.9%) 0.022 ms/op
Iteration   1: 5.251 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.152 ms/op
                 getUser·p0.99:   9.813 ms/op
                 getUser·p0.999:  21.882 ms/op
                 getUser·p0.9999: 28.833 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 5.282 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.562 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   10.819 ms/op
                 getUser·p0.999:  25.570 ms/op
                 getUser·p0.9999: 34.529 ms/op
                 getUser·p1.00:   35.062 ms/op

Iteration   3: 5.257 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.267 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   9.961 ms/op
                 getUser·p0.999:  25.892 ms/op
                 getUser·p0.9999: 30.619 ms/op
                 getUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182296
  mean =      5.263 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 95326 
    [ 5.000,  7.500) = 78281 
    [ 7.500, 10.000) = 6661 
    [10.000, 12.500) = 1282 
    [12.500, 15.000) = 387 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     24.294 ms/op
     p(99.9900) =     32.451 ms/op
     p(99.9990) =     35.178 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.134 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.291 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.302 ±(99.9%) 0.023 ms/op
Iteration   1: 6.231 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   5.886 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   12.141 ms/op
                 listUser·p0.999:  26.006 ms/op
                 listUser·p0.9999: 38.526 ms/op
                 listUser·p1.00:   39.387 ms/op

Iteration   2: 6.033 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  27.492 ms/op
                 listUser·p0.9999: 30.310 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 5.934 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.709 ms/op
                 listUser·p0.99:   10.224 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 23.252 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158279
  mean =      6.063 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 10383 
    [ 5.000,  7.500) = 136211 
    [ 7.500, 10.000) = 8592 
    [10.000, 12.500) = 1917 
    [12.500, 15.000) = 662 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      5.743 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.151 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     35.466 ms/op
     p(99.9990) =     39.311 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.975 ± 3.345  ops/ms
ClientPb.existUser                       thrpt       3   6.520 ± 0.653  ops/ms
ClientPb.getUser                         thrpt       3   6.074 ± 1.979  ops/ms
ClientPb.listUser                        thrpt       3   5.175 ± 1.279  ops/ms
ClientPb.createUser                       avgt       3   5.272 ± 0.923   ms/op
ClientPb.existUser                        avgt       3   5.142 ± 2.223   ms/op
ClientPb.getUser                          avgt       3   5.441 ± 2.222   ms/op
ClientPb.listUser                         avgt       3   6.011 ± 1.982   ms/op
ClientPb.createUser                     sample  184222   5.209 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.769           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.373           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.135           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.417           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.573           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  187701   5.111 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.745           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.201           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.176           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.040           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.312           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.470           ms/op
ClientPb.getUser                        sample  182296   5.263 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.446           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.256           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.294           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.717           ms/op
ClientPb.listUser                       sample  158279   6.063 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.551           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.297           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.466           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.387           ms/op
