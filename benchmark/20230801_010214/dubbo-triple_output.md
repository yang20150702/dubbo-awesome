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
# Warmup Iteration   1: 1.733 ops/ms
# Warmup Iteration   2: 3.721 ops/ms
# Warmup Iteration   3: 7.246 ops/ms
Iteration   1: 7.445 ops/ms
Iteration   2: 7.417 ops/ms
Iteration   3: 7.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.468 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (7.417, 7.468, 7.542), stdev = 0.066
  CI (99.9%): [6.271, 8.665] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 6.190 ops/ms
# Warmup Iteration   3: 7.720 ops/ms
Iteration   1: 8.298 ops/ms
Iteration   2: 8.438 ops/ms
Iteration   3: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.313 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (8.201, 8.313, 8.438), stdev = 0.119
  CI (99.9%): [6.135, 10.490] (assumes normal distribution)


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
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 6.038 ops/ms
# Warmup Iteration   3: 7.333 ops/ms
Iteration   1: 7.603 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.872 ±(99.9%) 4.675 ops/ms [Average]
  (min, avg, max) = (7.603, 7.872, 8.113), stdev = 0.256
  CI (99.9%): [3.197, 12.548] (assumes normal distribution)


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
# Warmup Iteration   1: 1.786 ops/ms
# Warmup Iteration   2: 4.792 ops/ms
# Warmup Iteration   3: 6.252 ops/ms
Iteration   1: 6.398 ops/ms
Iteration   2: 6.487 ops/ms
Iteration   3: 6.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.499 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (6.398, 6.499, 6.612), stdev = 0.107
  CI (99.9%): [4.542, 8.456] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.331 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.007 ms/op
Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
Iteration   2: 4.115 ±(99.9%) 0.011 ms/op
Iteration   3: 4.249 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.123 ±(99.9%) 2.215 ms/op [Average]
  (min, avg, max) = (4.006, 4.123, 4.249), stdev = 0.121
  CI (99.9%): [1.908, 6.338] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.652 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.007 ms/op
Iteration   1: 3.966 ±(99.9%) 0.004 ms/op
Iteration   2: 3.750 ±(99.9%) 0.011 ms/op
Iteration   3: 3.891 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.869 ±(99.9%) 2.004 ms/op [Average]
  (min, avg, max) = (3.750, 3.869, 3.966), stdev = 0.110
  CI (99.9%): [1.865, 5.874] (assumes normal distribution)


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
# Warmup Iteration   1: 15.174 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.005 ms/op
Iteration   1: 4.188 ±(99.9%) 0.009 ms/op
Iteration   2: 4.191 ±(99.9%) 0.006 ms/op
Iteration   3: 4.239 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.206 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (4.188, 4.206, 4.239), stdev = 0.028
  CI (99.9%): [3.686, 4.725] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.543 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.806 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.720 ±(99.9%) 0.010 ms/op
Iteration   1: 4.634 ±(99.9%) 0.013 ms/op
Iteration   2: 4.719 ±(99.9%) 0.012 ms/op
Iteration   3: 4.726 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.693 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (4.634, 4.693, 4.726), stdev = 0.051
  CI (99.9%): [3.760, 5.625] (assumes normal distribution)


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
# Warmup Iteration   1: 14.593 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.684 ±(99.9%) 0.022 ms/op
Iteration   1: 3.984 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  22.616 ms/op
                 createUser·p0.9999: 26.017 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.892 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.696 ms/op
                 createUser·p0.999:  23.162 ms/op
                 createUser·p0.9999: 26.422 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 4.023 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 31.364 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238989
  mean =      4.016 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 357 
    [ 2.500,  5.000) = 226457 
    [ 5.000,  7.500) = 10244 
    [ 7.500, 10.000) = 1366 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     22.513 ms/op
     p(99.9900) =     28.970 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 12.818 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.013 ms/op
Iteration   1: 3.896 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  16.450 ms/op
                 existUser·p0.9999: 30.330 ms/op
                 existUser·p1.00:   31.457 ms/op

Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  25.703 ms/op
                 existUser·p0.9999: 28.934 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.931 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  13.730 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249220
  mean =      3.850 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 239809 
    [ 5.000,  7.500) = 7702 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.866 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     15.629 ms/op
     p(99.9900) =     32.476 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 14.355 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.028 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.015 ms/op
Iteration   1: 4.242 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   4.088 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  13.808 ms/op
                 getUser·p0.9999: 31.061 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   2: 3.920 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.017 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  25.435 ms/op
                 getUser·p0.9999: 35.534 ms/op
                 getUser·p1.00:   39.256 ms/op

Iteration   3: 4.018 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  27.266 ms/op
                 getUser·p0.9999: 31.986 ms/op
                 getUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236567
  mean =      4.056 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 223714 
    [ 5.000,  7.500) = 10290 
    [ 7.500, 10.000) = 1539 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     24.871 ms/op
     p(99.9900) =     33.435 ms/op
     p(99.9990) =     37.260 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 14.444 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.993 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.866 ±(99.9%) 0.018 ms/op
Iteration   1: 4.923 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  25.199 ms/op
                 listUser·p0.9999: 27.772 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 4.864 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   8.800 ms/op
                 listUser·p0.999:  21.493 ms/op
                 listUser·p0.9999: 25.639 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 4.983 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  18.930 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194787
  mean =      4.923 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 144575 
    [ 5.000,  7.500) = 43836 
    [ 7.500, 10.000) = 4702 
    [10.000, 12.500) = 959 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.260 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.468 ± 1.197  ops/ms
ClientPb.existUser                       thrpt       3   8.313 ± 2.177  ops/ms
ClientPb.getUser                         thrpt       3   7.872 ± 4.675  ops/ms
ClientPb.listUser                        thrpt       3   6.499 ± 1.957  ops/ms
ClientPb.createUser                       avgt       3   4.123 ± 2.215   ms/op
ClientPb.existUser                        avgt       3   3.869 ± 2.004   ms/op
ClientPb.getUser                          avgt       3   4.206 ± 0.520   ms/op
ClientPb.listUser                         avgt       3   4.693 ± 0.932   ms/op
ClientPb.createUser                     sample  238989   4.016 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.970           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.342           ms/op
ClientPb.existUser                      sample  249220   3.850 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.866           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.629           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.476           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.537           ms/op
ClientPb.getUser                        sample  236567   4.056 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.925           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.871           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.256           ms/op
ClientPb.listUser                       sample  194787   4.923 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.513           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.692           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.870           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.508           ms/op
