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
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 3.527 ops/ms
# Warmup Iteration   3: 7.345 ops/ms
Iteration   1: 7.348 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 8.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.780 ±(99.9%) 6.862 ops/ms [Average]
  (min, avg, max) = (7.348, 7.780, 8.031), stdev = 0.376
  CI (99.9%): [0.918, 14.642] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 6.328 ops/ms
# Warmup Iteration   3: 7.876 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.291 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.301 ±(99.9%) 0.366 ops/ms [Average]
  (min, avg, max) = (8.288, 8.301, 8.324), stdev = 0.020
  CI (99.9%): [7.935, 8.666] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.091 ops/ms
# Warmup Iteration   2: 6.360 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.222 ±(99.9%) 2.579 ops/ms [Average]
  (min, avg, max) = (8.060, 8.222, 8.321), stdev = 0.141
  CI (99.9%): [5.643, 10.802] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 5.615 ops/ms
# Warmup Iteration   3: 6.567 ops/ms
Iteration   1: 6.735 ops/ms
Iteration   2: 7.089 ops/ms
Iteration   3: 6.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.900 ±(99.9%) 3.250 ops/ms [Average]
  (min, avg, max) = (6.735, 6.900, 7.089), stdev = 0.178
  CI (99.9%): [3.649, 10.150] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.656 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.006 ms/op
Iteration   1: 3.861 ±(99.9%) 0.009 ms/op
Iteration   2: 3.742 ±(99.9%) 0.004 ms/op
Iteration   3: 4.025 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.876 ±(99.9%) 2.586 ms/op [Average]
  (min, avg, max) = (3.742, 3.876, 4.025), stdev = 0.142
  CI (99.9%): [1.291, 6.462] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.259 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.004 ms/op
Iteration   1: 3.753 ±(99.9%) 0.004 ms/op
Iteration   2: 3.781 ±(99.9%) 0.004 ms/op
Iteration   3: 3.768 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.767 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.753, 3.767, 3.781), stdev = 0.014
  CI (99.9%): [3.507, 4.028] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 12.308 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.004 ms/op
Iteration   1: 4.083 ±(99.9%) 0.003 ms/op
Iteration   2: 3.998 ±(99.9%) 0.003 ms/op
Iteration   3: 4.102 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.061 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.998, 4.061, 4.102), stdev = 0.055
  CI (99.9%): [3.050, 5.073] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.270 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.141 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.584 ±(99.9%) 0.008 ms/op
Iteration   1: 4.610 ±(99.9%) 0.008 ms/op
Iteration   2: 4.800 ±(99.9%) 0.006 ms/op
Iteration   3: 4.638 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.682 ±(99.9%) 1.873 ms/op [Average]
  (min, avg, max) = (4.610, 4.682, 4.800), stdev = 0.103
  CI (99.9%): [2.809, 6.556] (assumes normal distribution)


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
# Warmup Iteration   1: 12.426 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.304 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.489 ±(99.9%) 0.018 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  23.778 ms/op
                 createUser·p0.9999: 26.968 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  13.854 ms/op
                 createUser·p0.9999: 32.347 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   3: 4.033 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  28.348 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238445
  mean =      4.025 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 408 
    [ 2.500,  5.000) = 225762 
    [ 5.000,  7.500) = 10285 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     31.500 ms/op
     p(99.9990) =     32.980 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 12.401 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.014 ms/op
Iteration   1: 3.956 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.071 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  13.264 ms/op
                 existUser·p0.9999: 34.504 ms/op
                 existUser·p1.00:   35.258 ms/op

Iteration   2: 3.868 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  15.191 ms/op
                 existUser·p0.9999: 28.368 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 3.872 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  28.946 ms/op
                 existUser·p0.9999: 33.555 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246211
  mean =      3.898 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 384 
    [ 2.500,  5.000) = 236079 
    [ 5.000,  7.500) = 7479 
    [ 7.500, 10.000) = 1589 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 12.803 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.013 ms/op
Iteration   1: 3.830 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  22.577 ms/op
                 getUser·p0.9999: 30.921 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  23.597 ms/op
                 getUser·p0.9999: 26.075 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  15.946 ms/op
                 getUser·p0.9999: 29.259 ms/op
                 getUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249624
  mean =      3.844 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 845 
    [ 2.500,  5.000) = 240247 
    [ 5.000,  7.500) = 7339 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     22.262 ms/op
     p(99.9900) =     29.409 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 15.227 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 5.482 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.875 ±(99.9%) 0.016 ms/op
Iteration   1: 4.721 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  23.901 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 4.624 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  17.723 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 4.500 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  15.218 ms/op
                 listUser·p0.9999: 18.899 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208019
  mean =      4.613 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 182616 
    [ 5.000,  7.500) = 22089 
    [ 7.500, 10.000) = 2409 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     27.555 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.780 ± 6.862  ops/ms
ClientPb.existUser                       thrpt       3   8.301 ± 0.366  ops/ms
ClientPb.getUser                         thrpt       3   8.222 ± 2.579  ops/ms
ClientPb.listUser                        thrpt       3   6.900 ± 3.250  ops/ms
ClientPb.createUser                       avgt       3   3.876 ± 2.586   ms/op
ClientPb.existUser                        avgt       3   3.767 ± 0.260   ms/op
ClientPb.getUser                          avgt       3   4.061 ± 1.011   ms/op
ClientPb.listUser                         avgt       3   4.682 ± 1.873   ms/op
ClientPb.createUser                     sample  238445   4.025 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.855           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  246211   3.898 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.520           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.356           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.237           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.686           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  249624   3.844 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.380           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.262           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.409           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  208019   4.613 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.481           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.608           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
