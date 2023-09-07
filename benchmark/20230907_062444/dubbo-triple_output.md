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
# Warmup Iteration   1: 0.966 ops/ms
# Warmup Iteration   2: 2.033 ops/ms
# Warmup Iteration   3: 4.592 ops/ms
Iteration   1: 5.305 ops/ms
Iteration   2: 5.486 ops/ms
Iteration   3: 5.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.465 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (5.305, 5.465, 5.603), stdev = 0.150
  CI (99.9%): [2.731, 8.198] (assumes normal distribution)


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
# Warmup Iteration   1: 1.400 ops/ms
# Warmup Iteration   2: 4.478 ops/ms
# Warmup Iteration   3: 5.881 ops/ms
Iteration   1: 5.928 ops/ms
Iteration   2: 5.896 ops/ms
Iteration   3: 6.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.001 ±(99.9%) 2.829 ops/ms [Average]
  (min, avg, max) = (5.896, 6.001, 6.179), stdev = 0.155
  CI (99.9%): [3.171, 8.830] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.502 ops/ms
# Warmup Iteration   2: 4.154 ops/ms
# Warmup Iteration   3: 5.495 ops/ms
Iteration   1: 5.610 ops/ms
Iteration   2: 5.636 ops/ms
Iteration   3: 5.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.623 ±(99.9%) 0.237 ops/ms [Average]
  (min, avg, max) = (5.610, 5.623, 5.636), stdev = 0.013
  CI (99.9%): [5.386, 5.860] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.265 ops/ms
# Warmup Iteration   2: 3.957 ops/ms
# Warmup Iteration   3: 4.496 ops/ms
Iteration   1: 4.615 ops/ms
Iteration   2: 4.839 ops/ms
Iteration   3: 4.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.703 ±(99.9%) 2.182 ops/ms [Average]
  (min, avg, max) = (4.615, 4.703, 4.839), stdev = 0.120
  CI (99.9%): [2.521, 6.885] (assumes normal distribution)


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
# Warmup Iteration   1: 22.742 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 7.479 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.047 ±(99.9%) 0.013 ms/op
Iteration   1: 5.913 ±(99.9%) 0.016 ms/op
Iteration   2: 5.709 ±(99.9%) 0.014 ms/op
Iteration   3: 5.724 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.782 ±(99.9%) 2.077 ms/op [Average]
  (min, avg, max) = (5.709, 5.782, 5.913), stdev = 0.114
  CI (99.9%): [3.706, 7.859] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.512 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.617 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.384 ±(99.9%) 0.006 ms/op
Iteration   1: 5.333 ±(99.9%) 0.010 ms/op
Iteration   2: 5.413 ±(99.9%) 0.011 ms/op
Iteration   3: 5.465 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.403 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (5.333, 5.403, 5.465), stdev = 0.067
  CI (99.9%): [4.190, 6.617] (assumes normal distribution)


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
# Warmup Iteration   1: 19.437 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.994 ±(99.9%) 0.008 ms/op
Iteration   1: 6.023 ±(99.9%) 0.006 ms/op
Iteration   2: 5.925 ±(99.9%) 0.012 ms/op
Iteration   3: 5.807 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.918 ±(99.9%) 1.972 ms/op [Average]
  (min, avg, max) = (5.807, 5.918, 6.023), stdev = 0.108
  CI (99.9%): [3.946, 7.891] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 22.252 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.897 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.896 ±(99.9%) 0.020 ms/op
Iteration   1: 6.834 ±(99.9%) 0.019 ms/op
Iteration   2: 6.742 ±(99.9%) 0.015 ms/op
Iteration   3: 6.619 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.732 ±(99.9%) 1.966 ms/op [Average]
  (min, avg, max) = (6.619, 6.732, 6.834), stdev = 0.108
  CI (99.9%): [4.766, 8.698] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.483 ±(99.9%) 0.418 ms/op
# Warmup Iteration   2: 7.826 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.615 ±(99.9%) 0.037 ms/op
Iteration   1: 5.850 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.605 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.569 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  16.949 ms/op
                 createUser·p0.9999: 30.310 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   2: 5.668 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.703 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  28.462 ms/op
                 createUser·p0.9999: 33.699 ms/op
                 createUser·p1.00:   42.402 ms/op

Iteration   3: 5.699 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.666 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.717 ms/op
                 createUser·p0.99:   11.517 ms/op
                 createUser·p0.999:  28.764 ms/op
                 createUser·p0.9999: 33.383 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167314
  mean =      5.738 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 32417 
    [ 5.000, 10.000) = 131995 
    [10.000, 15.000) = 2593 
    [15.000, 20.000) = 148 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 86 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     33.122 ms/op
     p(99.9990) =     42.225 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


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
# Warmup Iteration   1: 18.044 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 8.119 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 5.831 ±(99.9%) 0.028 ms/op
Iteration   1: 5.678 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.658 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.291 ms/op
                 existUser·p0.95:   8.815 ms/op
                 existUser·p0.99:   12.173 ms/op
                 existUser·p0.999:  26.466 ms/op
                 existUser·p0.9999: 29.470 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   2: 5.671 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   5.333 ms/op
                 existUser·p0.90:   7.004 ms/op
                 existUser·p0.95:   8.159 ms/op
                 existUser·p0.99:   11.764 ms/op
                 existUser·p0.999:  36.635 ms/op
                 existUser·p0.9999: 40.722 ms/op
                 existUser·p1.00:   41.157 ms/op

Iteration   3: 5.463 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.692 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  15.892 ms/op
                 existUser·p0.9999: 33.340 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171234
  mean =      5.602 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60197 
    [ 5.000, 10.000) = 107504 
    [10.000, 15.000) = 3133 
    [15.000, 20.000) = 239 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 64 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 49 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     17.918 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     41.157 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.425 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 7.859 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.097 ±(99.9%) 0.024 ms/op
Iteration   1: 5.935 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   5.587 ms/op
                 getUser·p0.90:   7.209 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   12.071 ms/op
                 getUser·p0.999:  29.002 ms/op
                 getUser·p0.9999: 31.989 ms/op
                 getUser·p1.00:   32.932 ms/op

Iteration   2: 5.848 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.405 ms/op
                 getUser·p0.99:   12.304 ms/op
                 getUser·p0.999:  29.590 ms/op
                 getUser·p0.9999: 34.214 ms/op
                 getUser·p1.00:   35.717 ms/op

Iteration   3: 5.745 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   3.002 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.863 ms/op
                 getUser·p0.999:  15.550 ms/op
                 getUser·p0.9999: 39.911 ms/op
                 getUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164252
  mean =      5.842 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 32931 
    [ 5.000, 10.000) = 127646 
    [10.000, 15.000) = 3200 
    [15.000, 20.000) = 223 
    [20.000, 25.000) = 70 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 76 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     28.213 ms/op
     p(99.9900) =     37.524 ms/op
     p(99.9990) =     40.899 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


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
# Warmup Iteration   1: 24.163 ±(99.9%) 0.466 ms/op
# Warmup Iteration   2: 8.794 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 7.242 ±(99.9%) 0.035 ms/op
Iteration   1: 6.668 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.960 ms/op
                 listUser·p0.999:  27.591 ms/op
                 listUser·p0.9999: 31.497 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   2: 6.835 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   14.680 ms/op
                 listUser·p0.999:  31.956 ms/op
                 listUser·p0.9999: 35.935 ms/op
                 listUser·p1.00:   36.307 ms/op

Iteration   3: 6.901 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   8.364 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.189 ms/op
                 listUser·p0.999:  31.316 ms/op
                 listUser·p0.9999: 36.034 ms/op
                 listUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141042
  mean =      6.800 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2492 
    [ 5.000,  7.500) = 115579 
    [ 7.500, 10.000) = 16648 
    [10.000, 12.500) = 4214 
    [12.500, 15.000) = 1246 
    [15.000, 17.500) = 446 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.462 ms/op
     p(50.0000) =      6.406 ms/op
     p(90.0000) =      8.233 ms/op
     p(95.0000) =      9.748 ms/op
     p(99.0000) =     13.730 ms/op
     p(99.9000) =     30.081 ms/op
     p(99.9900) =     35.755 ms/op
     p(99.9990) =     38.822 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.465 ± 2.733  ops/ms
ClientPb.existUser                       thrpt       3   6.001 ± 2.829  ops/ms
ClientPb.getUser                         thrpt       3   5.623 ± 0.237  ops/ms
ClientPb.listUser                        thrpt       3   4.703 ± 2.182  ops/ms
ClientPb.createUser                       avgt       3   5.782 ± 2.077   ms/op
ClientPb.existUser                        avgt       3   5.403 ± 1.214   ms/op
ClientPb.getUser                          avgt       3   5.918 ± 1.972   ms/op
ClientPb.listUser                         avgt       3   6.732 ± 1.966   ms/op
ClientPb.createUser                     sample  167314   5.738 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.971           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.092           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.874           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.122           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.402           ms/op
ClientPb.existUser                      sample  171234   5.602 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.274           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.747           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.918           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.404           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.157           ms/op
ClientPb.getUser                        sample  164252   5.842 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.511           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.249           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.600           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.213           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.524           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.026           ms/op
ClientPb.listUser                       sample  141042   6.800 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.406           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.748           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.081           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.755           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.387           ms/op
