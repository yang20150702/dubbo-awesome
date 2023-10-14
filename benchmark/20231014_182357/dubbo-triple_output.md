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
# Warmup Iteration   1: 1.242 ops/ms
# Warmup Iteration   2: 2.696 ops/ms
# Warmup Iteration   3: 5.801 ops/ms
Iteration   1: 6.020 ops/ms
Iteration   2: 6.621 ops/ms
Iteration   3: 6.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.427 ±(99.9%) 6.430 ops/ms [Average]
  (min, avg, max) = (6.020, 6.427, 6.640), stdev = 0.352
  CI (99.9%): [≈ 0, 12.857] (assumes normal distribution)


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
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 6.141 ops/ms
# Warmup Iteration   3: 6.728 ops/ms
Iteration   1: 6.972 ops/ms
Iteration   2: 6.778 ops/ms
Iteration   3: 6.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.871 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (6.778, 6.871, 6.972), stdev = 0.097
  CI (99.9%): [5.096, 8.645] (assumes normal distribution)


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
# Warmup Iteration   1: 2.082 ops/ms
# Warmup Iteration   2: 6.050 ops/ms
# Warmup Iteration   3: 6.593 ops/ms
Iteration   1: 6.696 ops/ms
Iteration   2: 6.708 ops/ms
Iteration   3: 6.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.696 ±(99.9%) 0.227 ops/ms [Average]
  (min, avg, max) = (6.683, 6.696, 6.708), stdev = 0.012
  CI (99.9%): [6.469, 6.922] (assumes normal distribution)


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
# Warmup Iteration   1: 1.701 ops/ms
# Warmup Iteration   2: 4.915 ops/ms
# Warmup Iteration   3: 5.702 ops/ms
Iteration   1: 5.737 ops/ms
Iteration   2: 5.895 ops/ms
Iteration   3: 5.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.852 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (5.737, 5.852, 5.923), stdev = 0.100
  CI (99.9%): [4.024, 7.679] (assumes normal distribution)


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
# Warmup Iteration   1: 16.482 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.532 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.938 ±(99.9%) 0.011 ms/op
Iteration   1: 4.667 ±(99.9%) 0.014 ms/op
Iteration   2: 4.889 ±(99.9%) 0.008 ms/op
Iteration   3: 4.991 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.849 ±(99.9%) 3.026 ms/op [Average]
  (min, avg, max) = (4.667, 4.849, 4.991), stdev = 0.166
  CI (99.9%): [1.823, 7.875] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.708 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.007 ms/op
Iteration   1: 4.520 ±(99.9%) 0.011 ms/op
Iteration   2: 4.412 ±(99.9%) 0.010 ms/op
Iteration   3: 4.542 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.491 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (4.412, 4.491, 4.542), stdev = 0.070
  CI (99.9%): [3.222, 5.761] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.124 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.629 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.007 ms/op
Iteration   1: 4.983 ±(99.9%) 0.010 ms/op
Iteration   2: 4.836 ±(99.9%) 0.009 ms/op
Iteration   3: 4.911 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.910 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.836, 4.910, 4.983), stdev = 0.074
  CI (99.9%): [3.568, 6.252] (assumes normal distribution)


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
# Warmup Iteration   1: 17.367 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.176 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.010 ms/op
Iteration   1: 5.614 ±(99.9%) 0.012 ms/op
Iteration   2: 5.575 ±(99.9%) 0.010 ms/op
Iteration   3: 5.595 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.595 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (5.575, 5.595, 5.614), stdev = 0.019
  CI (99.9%): [5.245, 5.944] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.615 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 6.029 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.023 ms/op
Iteration   1: 4.874 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   4.694 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.586 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  19.302 ms/op
                 createUser·p0.9999: 26.917 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 4.787 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.759 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  20.977 ms/op
                 createUser·p0.9999: 28.427 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 4.913 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   4.579 ms/op
                 createUser·p0.90:   6.119 ms/op
                 createUser·p0.95:   7.053 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  19.222 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 197428
  mean =      4.857 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 198 
    [ 2.500,  5.000) = 135268 
    [ 5.000,  7.500) = 55553 
    [ 7.500, 10.000) = 4890 
    [10.000, 12.500) = 935 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.679 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     19.815 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     29.467 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.318 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.981 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.020 ms/op
Iteration   1: 4.778 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  20.021 ms/op
                 existUser·p0.9999: 27.063 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 4.594 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.435 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.775 ms/op
                 existUser·p0.99:   9.159 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 28.746 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   3: 4.609 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   4.375 ms/op
                 existUser·p0.90:   5.456 ms/op
                 existUser·p0.95:   6.267 ms/op
                 existUser·p0.99:   9.290 ms/op
                 existUser·p0.999:  18.085 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 206092
  mean =      4.659 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 202 
    [ 2.500,  5.000) = 164016 
    [ 5.000,  7.500) = 35493 
    [ 7.500, 10.000) = 4783 
    [10.000, 12.500) = 986 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     27.059 ms/op
     p(99.9990) =     29.313 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 14.764 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.354 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.973 ±(99.9%) 0.018 ms/op
Iteration   1: 4.876 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   4.563 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   10.273 ms/op
                 getUser·p0.999:  23.954 ms/op
                 getUser·p0.9999: 26.393 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 4.826 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   7.160 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  15.619 ms/op
                 getUser·p0.9999: 27.975 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 5.172 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.416 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.692 ms/op
                 getUser·p0.99:   10.420 ms/op
                 getUser·p0.999:  22.679 ms/op
                 getUser·p0.9999: 28.004 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 193840
  mean =      4.953 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 135530 
    [ 5.000,  7.500) = 49131 
    [ 7.500, 10.000) = 7192 
    [10.000, 12.500) = 1127 
    [12.500, 15.000) = 422 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =      9.988 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     27.906 ms/op
     p(99.9990) =     28.510 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.360 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.840 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.803 ±(99.9%) 0.025 ms/op
Iteration   1: 5.593 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   5.177 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   11.485 ms/op
                 listUser·p0.999:  22.249 ms/op
                 listUser·p0.9999: 23.701 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 5.716 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  25.981 ms/op
                 listUser·p0.9999: 28.043 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   3: 5.425 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   6.518 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   11.468 ms/op
                 listUser·p0.999:  19.795 ms/op
                 listUser·p0.9999: 26.513 ms/op
                 listUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 172088
  mean =      5.575 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 67886 
    [ 5.000,  7.500) = 91897 
    [ 7.500, 10.000) = 8900 
    [10.000, 12.500) = 2251 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 264 
    [17.500, 20.000) = 196 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      8.192 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     27.191 ms/op
     p(99.9990) =     28.512 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.427 ± 6.430  ops/ms
ClientPb.existUser                       thrpt       3   6.871 ± 1.774  ops/ms
ClientPb.getUser                         thrpt       3   6.696 ± 0.227  ops/ms
ClientPb.listUser                        thrpt       3   5.852 ± 1.827  ops/ms
ClientPb.createUser                       avgt       3   4.849 ± 3.026   ms/op
ClientPb.existUser                        avgt       3   4.491 ± 1.270   ms/op
ClientPb.getUser                          avgt       3   4.910 ± 1.342   ms/op
ClientPb.listUser                         avgt       3   5.595 ± 0.349   ms/op
ClientPb.createUser                     sample  197428   4.857 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.679           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.470           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.017           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.786           ms/op
ClientPb.existUser                      sample  206092   4.659 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.435           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.825           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.059           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.622           ms/op
ClientPb.getUser                        sample  193840   4.953 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.416           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.430           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.906           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.541           ms/op
ClientPb.listUser                       sample  172088   5.575 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.993           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.192           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.534           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.249           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.191           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
