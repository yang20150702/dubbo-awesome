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
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 5.664 ops/ms
# Warmup Iteration   3: 9.450 ops/ms
Iteration   1: 9.888 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 9.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.796 ±(99.9%) 2.769 ops/ms [Average]
  (min, avg, max) = (9.621, 9.796, 9.888), stdev = 0.152
  CI (99.9%): [7.027, 12.565] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.171 ops/ms
# Warmup Iteration   2: 8.581 ops/ms
# Warmup Iteration   3: 9.993 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.186 ops/ms
Iteration   3: 10.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.210 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (10.174, 10.210, 10.271), stdev = 0.053
  CI (99.9%): [9.240, 11.181] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ops/ms
# Warmup Iteration   2: 9.266 ops/ms
# Warmup Iteration   3: 9.568 ops/ms
Iteration   1: 9.079 ops/ms
Iteration   2: 9.801 ops/ms
Iteration   3: 10.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.652 ±(99.9%) 9.385 ops/ms [Average]
  (min, avg, max) = (9.079, 9.652, 10.075), stdev = 0.514
  CI (99.9%): [0.267, 19.037] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.367 ops/ms
# Warmup Iteration   2: 7.645 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.280 ±(99.9%) 3.086 ops/ms [Average]
  (min, avg, max) = (8.104, 8.280, 8.441), stdev = 0.169
  CI (99.9%): [5.194, 11.366] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.004 ms/op
Iteration   1: 3.384 ±(99.9%) 0.006 ms/op
Iteration   2: 3.252 ±(99.9%) 0.002 ms/op
Iteration   3: 3.248 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.248, 3.295, 3.384), stdev = 0.077
  CI (99.9%): [1.883, 4.707] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.496 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.004 ms/op
Iteration   2: 3.169 ±(99.9%) 0.005 ms/op
Iteration   3: 3.169 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (3.125, 3.154, 3.169), stdev = 0.025
  CI (99.9%): [2.689, 3.620] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.077 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.005 ms/op
Iteration   1: 3.219 ±(99.9%) 0.003 ms/op
Iteration   2: 3.227 ±(99.9%) 0.003 ms/op
Iteration   3: 3.284 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.219, 3.243, 3.284), stdev = 0.035
  CI (99.9%): [2.596, 3.891] (assumes normal distribution)


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
# Warmup Iteration   1: 8.094 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.007 ms/op
Iteration   1: 3.856 ±(99.9%) 0.006 ms/op
Iteration   2: 3.827 ±(99.9%) 0.007 ms/op
Iteration   3: 3.678 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.787 ±(99.9%) 1.744 ms/op [Average]
  (min, avg, max) = (3.678, 3.787, 3.856), stdev = 0.096
  CI (99.9%): [2.043, 5.530] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.492 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  9.786 ms/op
                 createUser·p0.9999: 21.964 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.074 ms/op
                 createUser·p0.999:  13.042 ms/op
                 createUser·p0.9999: 24.514 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  15.368 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291487
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20871 
    [ 2.500,  5.000) = 262349 
    [ 5.000,  7.500) = 6965 
    [ 7.500, 10.000) = 818 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     15.360 ms/op
     p(99.9900) =     24.866 ms/op
     p(99.9990) =     27.626 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 8.000 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.507 ms/op
                 existUser·p0.9999: 19.637 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 20.790 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  9.650 ms/op
                 existUser·p0.9999: 20.380 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306546
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10229 
    [ 2.500,  5.000) = 289261 
    [ 5.000,  7.500) = 5742 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     13.360 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     21.232 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 9.647 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
Iteration   1: 3.216 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.507 ms/op
                 getUser·p0.999:  11.822 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 3.340 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  19.300 ms/op
                 getUser·p0.9999: 25.685 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  12.048 ms/op
                 getUser·p0.9999: 24.329 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292917
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14959 
    [ 2.500,  5.000) = 268871 
    [ 5.000,  7.500) = 7699 
    [ 7.500, 10.000) = 997 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     24.239 ms/op
     p(99.9990) =     26.154 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 8.892 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.012 ms/op
Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 19.943 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.804 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 16.089 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   3: 3.804 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.355 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 14.123 ms/op
                 listUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250530
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 240973 
    [ 5.000,  7.500) = 6719 
    [ 7.500, 10.000) = 2009 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     22.036 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.796 ± 2.769  ops/ms
ClientPb.existUser                       thrpt       3  10.210 ± 0.971  ops/ms
ClientPb.getUser                         thrpt       3   9.652 ± 9.385  ops/ms
ClientPb.listUser                        thrpt       3   8.280 ± 3.086  ops/ms
ClientPb.createUser                       avgt       3   3.295 ± 1.412   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 0.465   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 0.648   ms/op
ClientPb.listUser                         avgt       3   3.787 ± 1.744   ms/op
ClientPb.createUser                     sample  291487   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.940           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.360           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.866           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.541           ms/op
ClientPb.existUser                      sample  306546   3.129 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.025           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.931           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.360           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.447           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.430           ms/op
ClientPb.getUser                        sample  292917   3.277 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.253           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.042           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.239           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.345           ms/op
ClientPb.listUser                       sample  250530   3.830 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.550           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.200           ms/op
