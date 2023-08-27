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
# Warmup Iteration   1: 1.943 ops/ms
# Warmup Iteration   2: 5.584 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 9.145 ops/ms
Iteration   2: 9.063 ops/ms
Iteration   3: 9.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.139 ±(99.9%) 1.334 ops/ms [Average]
  (min, avg, max) = (9.063, 9.139, 9.209), stdev = 0.073
  CI (99.9%): [7.805, 10.473] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.042 ops/ms
# Warmup Iteration   2: 8.589 ops/ms
# Warmup Iteration   3: 9.195 ops/ms
Iteration   1: 9.513 ops/ms
Iteration   2: 9.830 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.547 ±(99.9%) 4.880 ops/ms [Average]
  (min, avg, max) = (9.299, 9.547, 9.830), stdev = 0.267
  CI (99.9%): [4.668, 14.427] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.116 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.073 ops/ms
Iteration   2: 8.857 ops/ms
Iteration   3: 9.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.047 ±(99.9%) 3.260 ops/ms [Average]
  (min, avg, max) = (8.857, 9.047, 9.211), stdev = 0.179
  CI (99.9%): [5.786, 12.307] (assumes normal distribution)


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
# Warmup Iteration   1: 2.796 ops/ms
# Warmup Iteration   2: 7.223 ops/ms
# Warmup Iteration   3: 7.781 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.913 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (7.879, 7.913, 7.971), stdev = 0.050
  CI (99.9%): [6.996, 8.831] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.749 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.008 ms/op
Iteration   1: 3.558 ±(99.9%) 0.006 ms/op
Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
Iteration   3: 3.370 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.455 ±(99.9%) 1.738 ms/op [Average]
  (min, avg, max) = (3.370, 3.455, 3.558), stdev = 0.095
  CI (99.9%): [1.717, 5.192] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.130 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.006 ms/op
Iteration   1: 3.391 ±(99.9%) 0.006 ms/op
Iteration   2: 3.358 ±(99.9%) 0.004 ms/op
Iteration   3: 3.292 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.347 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.292, 3.347, 3.391), stdev = 0.050
  CI (99.9%): [2.430, 4.264] (assumes normal distribution)


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
# Warmup Iteration   1: 8.311 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.006 ms/op
Iteration   1: 3.491 ±(99.9%) 0.008 ms/op
Iteration   2: 3.581 ±(99.9%) 0.003 ms/op
Iteration   3: 3.489 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.520 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.489, 3.520, 3.581), stdev = 0.052
  CI (99.9%): [2.566, 4.475] (assumes normal distribution)


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
# Warmup Iteration   1: 11.020 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.007 ms/op
Iteration   1: 4.011 ±(99.9%) 0.010 ms/op
Iteration   2: 4.112 ±(99.9%) 0.007 ms/op
Iteration   3: 4.076 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.066 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (4.011, 4.066, 4.112), stdev = 0.051
  CI (99.9%): [3.129, 5.004] (assumes normal distribution)


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
# Warmup Iteration   1: 9.107 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.011 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.204 ms/op
                 createUser·p0.999:  19.632 ms/op
                 createUser·p0.9999: 23.000 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.495 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  22.038 ms/op
                 createUser·p0.9999: 27.670 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   3: 3.535 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  19.943 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272720
  mean =      3.518 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3331 
    [ 2.500,  5.000) = 262238 
    [ 5.000,  7.500) = 5145 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     19.867 ms/op
     p(99.9900) =     27.713 ms/op
     p(99.9990) =     29.256 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 8.528 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 24.248 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 23.790 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.445 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  14.628 ms/op
                 existUser·p0.9999: 25.255 ms/op
                 existUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288660
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16780 
    [ 2.500,  5.000) = 266411 
    [ 5.000,  7.500) = 4256 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     12.769 ms/op
     p(99.9900) =     24.777 ms/op
     p(99.9990) =     25.913 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 8.952 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.013 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 27.714 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   2: 3.491 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.815 ms/op
                 getUser·p0.999:  21.659 ms/op
                 getUser·p0.9999: 32.834 ms/op
                 getUser·p1.00:   33.128 ms/op

Iteration   3: 3.449 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  19.739 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276641
  mean =      3.467 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4139 
    [ 2.500,  5.000) = 262549 
    [ 5.000,  7.500) = 8249 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.752 ms/op
     p(99.9900) =     31.053 ms/op
     p(99.9990) =     33.103 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 11.311 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.012 ms/op
Iteration   1: 4.244 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   8.997 ms/op
                 listUser·p0.999:  20.055 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 17.769 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   8.383 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 16.335 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233053
  mean =      4.120 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 220352 
    [ 5.000,  7.500) = 8778 
    [ 7.500, 10.000) = 2644 
    [10.000, 12.500) = 638 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.697 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.139 ± 1.334  ops/ms
ClientPb.existUser                       thrpt       3   9.547 ± 4.880  ops/ms
ClientPb.getUser                         thrpt       3   9.047 ± 3.260  ops/ms
ClientPb.listUser                        thrpt       3   7.913 ± 0.918  ops/ms
ClientPb.createUser                       avgt       3   3.455 ± 1.738   ms/op
ClientPb.existUser                        avgt       3   3.347 ± 0.917   ms/op
ClientPb.getUser                          avgt       3   3.520 ± 0.955   ms/op
ClientPb.listUser                         avgt       3   4.066 ± 0.937   ms/op
ClientPb.createUser                     sample  272720   3.518 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.867           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  288660   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.858           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.769           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.777           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.149           ms/op
ClientPb.getUser                        sample  276641   3.467 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.303           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.752           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.128           ms/op
ClientPb.listUser                       sample  233053   4.120 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.673           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.040           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.774           ms/op
