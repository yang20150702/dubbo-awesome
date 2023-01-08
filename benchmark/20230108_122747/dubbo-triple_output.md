# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.260 ops/ms
# Warmup Iteration   2: 2.793 ops/ms
# Warmup Iteration   3: 5.862 ops/ms
Iteration   1: 6.020 ops/ms
Iteration   2: 6.106 ops/ms
Iteration   3: 6.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.146 ±(99.9%) 2.717 ops/ms [Average]
  (min, avg, max) = (6.020, 6.146, 6.310), stdev = 0.149
  CI (99.9%): [3.429, 8.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.712 ops/ms
# Warmup Iteration   2: 5.012 ops/ms
# Warmup Iteration   3: 6.666 ops/ms
Iteration   1: 6.500 ops/ms
Iteration   2: 6.441 ops/ms
Iteration   3: 6.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.487 ±(99.9%) 0.757 ops/ms [Average]
  (min, avg, max) = (6.441, 6.487, 6.521), stdev = 0.041
  CI (99.9%): [5.730, 7.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.598 ops/ms
# Warmup Iteration   2: 4.610 ops/ms
# Warmup Iteration   3: 5.956 ops/ms
Iteration   1: 6.225 ops/ms
Iteration   2: 6.102 ops/ms
Iteration   3: 6.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.163 ±(99.9%) 1.126 ops/ms [Average]
  (min, avg, max) = (6.102, 6.163, 6.225), stdev = 0.062
  CI (99.9%): [5.038, 7.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.722 ops/ms
# Warmup Iteration   2: 4.498 ops/ms
# Warmup Iteration   3: 5.230 ops/ms
Iteration   1: 5.345 ops/ms
Iteration   2: 5.417 ops/ms
Iteration   3: 5.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.421 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (5.345, 5.421, 5.501), stdev = 0.078
  CI (99.9%): [3.996, 6.845] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.631 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.145 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.402 ±(99.9%) 0.005 ms/op
Iteration   1: 5.018 ±(99.9%) 0.016 ms/op
Iteration   2: 5.172 ±(99.9%) 0.014 ms/op
Iteration   3: 5.040 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.077 ±(99.9%) 1.523 ms/op [Average]
  (min, avg, max) = (5.018, 5.077, 5.172), stdev = 0.083
  CI (99.9%): [3.553, 6.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.192 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.962 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.005 ms/op
Iteration   1: 4.859 ±(99.9%) 0.010 ms/op
Iteration   2: 4.900 ±(99.9%) 0.014 ms/op
Iteration   3: 4.903 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.887 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (4.859, 4.887, 4.903), stdev = 0.024
  CI (99.9%): [4.441, 5.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.838 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.965 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.989 ±(99.9%) 0.015 ms/op
Iteration   1: 5.307 ±(99.9%) 0.011 ms/op
Iteration   2: 5.169 ±(99.9%) 0.016 ms/op
Iteration   3: 5.083 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.186 ±(99.9%) 2.064 ms/op [Average]
  (min, avg, max) = (5.083, 5.186, 5.307), stdev = 0.113
  CI (99.9%): [3.122, 7.250] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.854 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.824 ±(99.9%) 0.018 ms/op
Iteration   1: 5.725 ±(99.9%) 0.021 ms/op
Iteration   2: 5.788 ±(99.9%) 0.012 ms/op
Iteration   3: 5.889 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.801 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (5.725, 5.801, 5.889), stdev = 0.083
  CI (99.9%): [4.285, 7.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.125 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.232 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.542 ±(99.9%) 0.025 ms/op
Iteration   1: 5.194 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.315 ms/op
                 createUser·p0.99:   9.830 ms/op
                 createUser·p0.999:  23.134 ms/op
                 createUser·p0.9999: 28.044 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 5.075 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  24.905 ms/op
                 createUser·p0.9999: 28.427 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 4.926 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.417 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   5.923 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   8.014 ms/op
                 createUser·p0.999:  15.804 ms/op
                 createUser·p0.9999: 32.850 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189446
  mean =      5.063 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 114143 
    [ 5.000,  7.500) = 69750 
    [ 7.500, 10.000) = 4406 
    [10.000, 12.500) = 683 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     24.729 ms/op
     p(99.9900) =     32.409 ms/op
     p(99.9990) =     33.332 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.614 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 5.404 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.008 ±(99.9%) 0.019 ms/op
Iteration   1: 4.871 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.048 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.837 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  19.280 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   2: 4.904 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  23.691 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 4.798 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   8.241 ms/op
                 existUser·p0.999:  26.022 ms/op
                 existUser·p0.9999: 37.773 ms/op
                 existUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197448
  mean =      4.857 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 143780 
    [ 5.000,  7.500) = 48271 
    [ 7.500, 10.000) = 4124 
    [10.000, 12.500) = 681 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     23.808 ms/op
     p(99.9900) =     34.245 ms/op
     p(99.9990) =     38.144 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.138 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.941 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.021 ms/op
Iteration   1: 5.182 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.044 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   7.299 ms/op
                 getUser·p0.99:   11.354 ms/op
                 getUser·p0.999:  22.012 ms/op
                 getUser·p0.9999: 27.315 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 5.065 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.793 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.933 ms/op
                 getUser·p0.999:  22.681 ms/op
                 getUser·p0.9999: 28.375 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 4.943 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.874 ms/op
                 getUser·p0.95:   6.423 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  26.879 ms/op
                 getUser·p0.9999: 31.966 ms/op
                 getUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 189529
  mean =      5.061 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 119193 
    [ 5.000,  7.500) = 63999 
    [ 7.500, 10.000) = 4221 
    [10.000, 12.500) = 1133 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     24.214 ms/op
     p(99.9900) =     30.672 ms/op
     p(99.9990) =     33.082 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.052 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.998 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.798 ±(99.9%) 0.021 ms/op
Iteration   1: 6.136 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.888 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.928 ms/op
                 listUser·p0.99:   11.878 ms/op
                 listUser·p0.999:  24.236 ms/op
                 listUser·p0.9999: 28.645 ms/op
                 listUser·p1.00:   31.130 ms/op

Iteration   2: 5.857 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  27.116 ms/op
                 listUser·p0.9999: 30.429 ms/op
                 listUser·p1.00:   31.785 ms/op

Iteration   3: 5.961 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.004 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  23.029 ms/op
                 listUser·p0.9999: 27.862 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160338
  mean =      5.982 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 11513 
    [ 5.000,  7.500) = 138467 
    [ 7.500, 10.000) = 7322 
    [10.000, 12.500) = 1998 
    [12.500, 15.000) = 514 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.004 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     24.827 ms/op
     p(99.9900) =     28.994 ms/op
     p(99.9990) =     31.726 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.146 ± 2.717  ops/ms
ClientPb.existUser                       thrpt       3   6.487 ± 0.757  ops/ms
ClientPb.getUser                         thrpt       3   6.163 ± 1.126  ops/ms
ClientPb.listUser                        thrpt       3   5.421 ± 1.425  ops/ms
ClientPb.createUser                       avgt       3   5.077 ± 1.523   ms/op
ClientPb.existUser                        avgt       3   4.887 ± 0.446   ms/op
ClientPb.getUser                          avgt       3   5.186 ± 2.064   ms/op
ClientPb.listUser                         avgt       3   5.801 ± 1.516   ms/op
ClientPb.createUser                     sample  189446   5.063 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.799           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.011           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.729           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.409           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  197448   4.857 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.595           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.060           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.808           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.245           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.207           ms/op
ClientPb.getUser                        sample  189529   5.061 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.273           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.214           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.672           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.522           ms/op
ClientPb.listUser                       sample  160338   5.982 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.978           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.272           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.827           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.785           ms/op
