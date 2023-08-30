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
# Warmup Iteration   1: 1.803 ops/ms
# Warmup Iteration   2: 4.116 ops/ms
# Warmup Iteration   3: 7.210 ops/ms
Iteration   1: 7.396 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.821 ±(99.9%) 6.737 ops/ms [Average]
  (min, avg, max) = (7.396, 7.821, 8.054), stdev = 0.369
  CI (99.9%): [1.084, 14.558] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.163 ops/ms
# Warmup Iteration   2: 7.174 ops/ms
# Warmup Iteration   3: 8.069 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 8.245 ops/ms
Iteration   3: 8.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.287 ±(99.9%) 0.678 ops/ms [Average]
  (min, avg, max) = (8.245, 8.287, 8.314), stdev = 0.037
  CI (99.9%): [7.609, 8.966] (assumes normal distribution)


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
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 6.302 ops/ms
# Warmup Iteration   3: 7.813 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 7.982 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.999 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (7.971, 7.999, 8.045), stdev = 0.040
  CI (99.9%): [7.278, 8.721] (assumes normal distribution)


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
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 4.800 ops/ms
# Warmup Iteration   3: 6.082 ops/ms
Iteration   1: 6.525 ops/ms
Iteration   2: 6.445 ops/ms
Iteration   3: 6.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.551 ±(99.9%) 2.203 ops/ms [Average]
  (min, avg, max) = (6.445, 6.551, 6.682), stdev = 0.121
  CI (99.9%): [4.348, 8.753] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.663 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.945 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.004 ms/op
Iteration   1: 4.186 ±(99.9%) 0.006 ms/op
Iteration   2: 4.023 ±(99.9%) 0.008 ms/op
Iteration   3: 4.201 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.136 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (4.023, 4.136, 4.201), stdev = 0.099
  CI (99.9%): [2.332, 5.941] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.966 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.005 ms/op
Iteration   1: 3.924 ±(99.9%) 0.010 ms/op
Iteration   2: 4.024 ±(99.9%) 0.005 ms/op
Iteration   3: 4.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.986 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.924, 3.986, 4.024), stdev = 0.055
  CI (99.9%): [2.986, 4.987] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.602 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.005 ms/op
Iteration   1: 4.193 ±(99.9%) 0.005 ms/op
Iteration   2: 4.132 ±(99.9%) 0.012 ms/op
Iteration   3: 3.964 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.096 ±(99.9%) 2.161 ms/op [Average]
  (min, avg, max) = (3.964, 4.096, 4.193), stdev = 0.118
  CI (99.9%): [1.936, 6.257] (assumes normal distribution)


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
# Warmup Iteration   1: 14.694 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.013 ms/op
Iteration   1: 4.882 ±(99.9%) 0.014 ms/op
Iteration   2: 4.827 ±(99.9%) 0.011 ms/op
Iteration   3: 4.586 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.765 ±(99.9%) 2.875 ms/op [Average]
  (min, avg, max) = (4.586, 4.765, 4.882), stdev = 0.158
  CI (99.9%): [1.890, 7.640] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.060 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.850 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.554 ±(99.9%) 0.020 ms/op
Iteration   1: 4.046 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   8.151 ms/op
                 createUser·p0.999:  21.725 ms/op
                 createUser·p0.9999: 23.858 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.796 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.227 ms/op
                 createUser·p0.999:  13.926 ms/op
                 createUser·p0.9999: 29.262 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 4.051 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  25.429 ms/op
                 createUser·p0.9999: 29.888 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238044
  mean =      4.031 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 224069 
    [ 5.000,  7.500) = 11002 
    [ 7.500, 10.000) = 1901 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     22.281 ms/op
     p(99.9900) =     29.320 ms/op
     p(99.9990) =     31.342 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 12.067 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.571 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.012 ms/op
Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  11.488 ms/op
                 existUser·p0.9999: 35.167 ms/op
                 existUser·p1.00:   36.962 ms/op

Iteration   2: 4.040 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   8.307 ms/op
                 existUser·p0.999:  25.100 ms/op
                 existUser·p0.9999: 27.069 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   3: 3.936 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.386 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   7.723 ms/op
                 existUser·p0.999:  19.763 ms/op
                 existUser·p0.9999: 37.464 ms/op
                 existUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241077
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 345 
    [ 2.500,  5.000) = 228641 
    [ 5.000,  7.500) = 9522 
    [ 7.500, 10.000) = 1832 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     20.112 ms/op
     p(99.9900) =     35.710 ms/op
     p(99.9990) =     38.570 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 13.985 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.844 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.012 ms/op
Iteration   1: 4.341 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   7.266 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  19.792 ms/op
                 getUser·p0.9999: 25.797 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 4.103 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  12.157 ms/op
                 getUser·p0.9999: 22.014 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 4.029 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.362 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 24.940 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231113
  mean =      4.154 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 215423 
    [ 5.000,  7.500) = 10702 
    [ 7.500, 10.000) = 3738 
    [10.000, 12.500) = 792 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     19.522 ms/op
     p(99.9900) =     24.933 ms/op
     p(99.9990) =     26.413 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 14.765 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 6.449 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.996 ±(99.9%) 0.017 ms/op
Iteration   1: 5.022 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  24.292 ms/op
                 listUser·p0.9999: 26.911 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.880 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  18.658 ms/op
                 listUser·p0.9999: 26.174 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   3: 5.084 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  20.380 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192162
  mean =      4.994 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 138016 
    [ 5.000,  7.500) = 46743 
    [ 7.500, 10.000) = 5835 
    [10.000, 12.500) = 960 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     26.521 ms/op
     p(99.9990) =     27.243 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.821 ± 6.737  ops/ms
ClientPb.existUser                       thrpt       3   8.287 ± 0.678  ops/ms
ClientPb.getUser                         thrpt       3   7.999 ± 0.722  ops/ms
ClientPb.listUser                        thrpt       3   6.551 ± 2.203  ops/ms
ClientPb.createUser                       avgt       3   4.136 ± 1.805   ms/op
ClientPb.existUser                        avgt       3   3.986 ± 1.001   ms/op
ClientPb.getUser                          avgt       3   4.096 ± 2.161   ms/op
ClientPb.listUser                         avgt       3   4.765 ± 2.875   ms/op
ClientPb.createUser                     sample  238044   4.031 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.784           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.309           ms/op
ClientPb.existUser                      sample  241077   3.977 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.235           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.660           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.112           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.710           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.191           ms/op
ClientPb.getUser                        sample  231113   4.154 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.690           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.618           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.522           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.933           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.477           ms/op
ClientPb.listUser                       sample  192162   4.994 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.989           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.249           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
