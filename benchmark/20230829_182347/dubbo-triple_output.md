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
# Warmup Iteration   1: 1.694 ops/ms
# Warmup Iteration   2: 3.793 ops/ms
# Warmup Iteration   3: 7.444 ops/ms
Iteration   1: 7.425 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 7.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.821 ±(99.9%) 6.353 ops/ms [Average]
  (min, avg, max) = (7.425, 7.821, 8.081), stdev = 0.348
  CI (99.9%): [1.468, 14.173] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.431 ops/ms
# Warmup Iteration   2: 7.401 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 8.103 ops/ms
Iteration   2: 8.181 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.299 ±(99.9%) 4.993 ops/ms [Average]
  (min, avg, max) = (8.103, 8.299, 8.611), stdev = 0.274
  CI (99.9%): [3.305, 13.292] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
# Warmup Iteration   2: 6.294 ops/ms
# Warmup Iteration   3: 7.568 ops/ms
Iteration   1: 7.591 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 7.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.808 ±(99.9%) 4.634 ops/ms [Average]
  (min, avg, max) = (7.591, 7.808, 8.087), stdev = 0.254
  CI (99.9%): [3.174, 12.442] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 6.606 ops/ms
Iteration   1: 6.826 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.798 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (6.777, 6.798, 6.826), stdev = 0.025
  CI (99.9%): [6.333, 7.263] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.800 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.005 ms/op
Iteration   1: 3.961 ±(99.9%) 0.003 ms/op
Iteration   2: 3.853 ±(99.9%) 0.004 ms/op
Iteration   3: 3.908 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.907 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.853, 3.907, 3.961), stdev = 0.054
  CI (99.9%): [2.917, 4.898] (assumes normal distribution)


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
# Warmup Iteration   1: 12.101 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.004 ms/op
Iteration   1: 3.750 ±(99.9%) 0.005 ms/op
Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
Iteration   3: 3.794 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.763 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.744, 3.763, 3.794), stdev = 0.028
  CI (99.9%): [3.257, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 13.971 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.004 ms/op
Iteration   1: 4.105 ±(99.9%) 0.005 ms/op
Iteration   2: 4.043 ±(99.9%) 0.010 ms/op
Iteration   3: 3.974 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.041 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (3.974, 4.041, 4.105), stdev = 0.066
  CI (99.9%): [2.844, 5.238] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.342 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.008 ms/op
Iteration   1: 4.743 ±(99.9%) 0.012 ms/op
Iteration   2: 4.767 ±(99.9%) 0.009 ms/op
Iteration   3: 4.747 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.752 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (4.743, 4.752, 4.767), stdev = 0.013
  CI (99.9%): [4.521, 4.983] (assumes normal distribution)


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
# Warmup Iteration   1: 12.205 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.157 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.463 ±(99.9%) 0.019 ms/op
Iteration   1: 4.109 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   8.807 ms/op
                 createUser·p0.999:  25.448 ms/op
                 createUser·p0.9999: 31.038 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   2: 3.977 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.077 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  13.542 ms/op
                 createUser·p0.9999: 44.234 ms/op
                 createUser·p1.00:   44.499 ms/op

Iteration   3: 3.973 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  27.708 ms/op
                 createUser·p0.9999: 30.833 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238718
  mean =      4.018 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 223347 
    [ 5.000, 10.000) = 14283 
    [10.000, 15.000) = 762 
    [15.000, 20.000) = 68 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 130 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     25.404 ms/op
     p(99.9900) =     43.459 ms/op
     p(99.9990) =     44.448 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.163 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.013 ms/op
Iteration   1: 3.874 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  21.934 ms/op
                 existUser·p0.9999: 26.213 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 4.147 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   6.225 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  14.547 ms/op
                 existUser·p0.9999: 38.292 ms/op
                 existUser·p1.00:   39.453 ms/op

Iteration   3: 3.877 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  12.148 ms/op
                 existUser·p0.9999: 28.327 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242303
  mean =      3.962 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 228286 
    [ 5.000,  7.500) = 10619 
    [ 7.500, 10.000) = 2424 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     14.511 ms/op
     p(99.9900) =     35.032 ms/op
     p(99.9990) =     38.697 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 12.896 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.015 ms/op
Iteration   1: 4.136 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   6.308 ms/op
                 getUser·p0.99:   10.309 ms/op
                 getUser·p0.999:  23.527 ms/op
                 getUser·p0.9999: 29.336 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 4.020 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   8.298 ms/op
                 getUser·p0.999:  15.106 ms/op
                 getUser·p0.9999: 31.299 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 3.923 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  27.296 ms/op
                 getUser·p0.9999: 30.043 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238499
  mean =      4.025 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 225984 
    [ 5.000,  7.500) = 7692 
    [ 7.500, 10.000) = 3265 
    [10.000, 12.500) = 977 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     23.511 ms/op
     p(99.9900) =     30.774 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 14.552 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.155 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.913 ±(99.9%) 0.020 ms/op
Iteration   1: 4.812 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  25.199 ms/op
                 listUser·p0.9999: 28.498 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   2: 4.679 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 4.730 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.703 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  17.498 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202454
  mean =      4.740 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 173910 
    [ 5.000,  7.500) = 22880 
    [ 7.500, 10.000) = 4294 
    [10.000, 12.500) = 769 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     26.632 ms/op
     p(99.9990) =     29.326 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.821 ± 6.353  ops/ms
ClientPb.existUser                       thrpt       3   8.299 ± 4.993  ops/ms
ClientPb.getUser                         thrpt       3   7.808 ± 4.634  ops/ms
ClientPb.listUser                        thrpt       3   6.798 ± 0.465  ops/ms
ClientPb.createUser                       avgt       3   3.907 ± 0.991   ms/op
ClientPb.existUser                        avgt       3   3.763 ± 0.506   ms/op
ClientPb.getUser                          avgt       3   4.041 ± 1.197   ms/op
ClientPb.listUser                         avgt       3   4.752 ± 0.231   ms/op
ClientPb.createUser                     sample  238718   4.018 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.620           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.126           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.404           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.459           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.499           ms/op
ClientPb.existUser                      sample  242303   3.962 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.063           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.489           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.873           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.511           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.032           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.453           ms/op
ClientPb.getUser                        sample  238499   4.025 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.782           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.511           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.774           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  202454   4.740 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.087           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.632           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278           ms/op
