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
# Warmup Iteration   1: 2.493 ops/ms
# Warmup Iteration   2: 6.310 ops/ms
# Warmup Iteration   3: 9.067 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.642 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (9.587, 9.642, 9.688), stdev = 0.051
  CI (99.9%): [8.706, 10.579] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ops/ms
# Warmup Iteration   2: 9.639 ops/ms
# Warmup Iteration   3: 9.826 ops/ms
Iteration   1: 10.441 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.340 ±(99.9%) 4.946 ops/ms [Average]
  (min, avg, max) = (10.033, 10.340, 10.547), stdev = 0.271
  CI (99.9%): [5.395, 15.286] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.827 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 9.675 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 9.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.001 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (9.947, 10.001, 10.078), stdev = 0.069
  CI (99.9%): [8.749, 11.253] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ops/ms
# Warmup Iteration   2: 7.806 ops/ms
# Warmup Iteration   3: 8.108 ops/ms
Iteration   1: 8.468 ops/ms
Iteration   2: 8.490 ops/ms
Iteration   3: 8.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.479 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (8.468, 8.479, 8.490), stdev = 0.011
  CI (99.9%): [8.269, 8.688] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.314 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.007 ms/op
Iteration   1: 3.184 ±(99.9%) 0.009 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.267 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.199 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.146, 3.199, 3.267), stdev = 0.062
  CI (99.9%): [2.067, 4.331] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.517 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.210 ±(99.9%) 0.006 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.101, 3.149, 3.210), stdev = 0.055
  CI (99.9%): [2.138, 4.160] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.380 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
Iteration   1: 3.339 ±(99.9%) 0.004 ms/op
Iteration   2: 3.144 ±(99.9%) 0.005 ms/op
Iteration   3: 3.304 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.262 ±(99.9%) 1.892 ms/op [Average]
  (min, avg, max) = (3.144, 3.262, 3.339), stdev = 0.104
  CI (99.9%): [1.370, 5.155] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.186 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.006 ms/op
Iteration   1: 3.813 ±(99.9%) 0.006 ms/op
Iteration   2: 3.739 ±(99.9%) 0.009 ms/op
Iteration   3: 3.798 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.783 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.739, 3.783, 3.813), stdev = 0.039
  CI (99.9%): [3.078, 4.489] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.610 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.011 ms/op
Iteration   1: 3.131 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  10.877 ms/op
                 createUser·p0.9999: 20.670 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  16.800 ms/op
                 createUser·p0.9999: 27.967 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296175
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22452 
    [ 2.500,  5.000) = 266477 
    [ 5.000,  7.500) = 5853 
    [ 7.500, 10.000) = 897 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     18.082 ms/op
     p(99.9900) =     27.157 ms/op
     p(99.9990) =     28.348 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.368 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.009 ms/op
Iteration   1: 3.246 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  15.442 ms/op
                 existUser·p0.9999: 22.423 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.289 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  10.223 ms/op
                 existUser·p0.9999: 29.050 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  16.073 ms/op
                 existUser·p0.9999: 24.789 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287559
  mean =      3.336 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13709 
    [ 2.500,  5.000) = 264593 
    [ 5.000,  7.500) = 7445 
    [ 7.500, 10.000) = 1334 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     27.181 ms/op
     p(99.9990) =     29.536 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.939 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.014 ms/op
Iteration   1: 3.339 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 26.719 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  20.184 ms/op
                 getUser·p0.9999: 23.967 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.356 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286956
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6617 
    [ 2.500,  5.000) = 273311 
    [ 5.000,  7.500) = 5315 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     25.130 ms/op
     p(99.9990) =     27.038 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.945 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.015 ms/op
Iteration   1: 4.020 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  17.772 ms/op
                 listUser·p0.9999: 28.936 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 3.936 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 15.860 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.944 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.685 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 14.351 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241872
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 232092 
    [ 5.000,  7.500) = 6491 
    [ 7.500, 10.000) = 2284 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     27.343 ms/op
     p(99.9990) =     30.269 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.642 ± 0.937  ops/ms
ClientPb.existUser                       thrpt       3  10.340 ± 4.946  ops/ms
ClientPb.getUser                         thrpt       3  10.001 ± 1.252  ops/ms
ClientPb.listUser                        thrpt       3   8.479 ± 0.209  ops/ms
ClientPb.createUser                       avgt       3   3.199 ± 1.132   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 1.011   ms/op
ClientPb.getUser                          avgt       3   3.262 ± 1.892   ms/op
ClientPb.listUser                         avgt       3   3.783 ± 0.706   ms/op
ClientPb.createUser                     sample  296175   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.082           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.157           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  287559   3.336 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.192           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.056           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.181           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.753           ms/op
ClientPb.getUser                        sample  286956   3.346 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.000           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.878           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.130           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  241872   3.967 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.352           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.343           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.409           ms/op
