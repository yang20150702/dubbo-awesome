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
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 3.416 ops/ms
# Warmup Iteration   3: 6.971 ops/ms
Iteration   1: 6.982 ops/ms
Iteration   2: 7.143 ops/ms
Iteration   3: 7.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.208 ±(99.9%) 4.831 ops/ms [Average]
  (min, avg, max) = (6.982, 7.208, 7.500), stdev = 0.265
  CI (99.9%): [2.378, 12.039] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.193 ops/ms
# Warmup Iteration   2: 7.364 ops/ms
# Warmup Iteration   3: 7.705 ops/ms
Iteration   1: 8.436 ops/ms
Iteration   2: 8.569 ops/ms
Iteration   3: 8.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.425 ±(99.9%) 2.732 ops/ms [Average]
  (min, avg, max) = (8.270, 8.425, 8.569), stdev = 0.150
  CI (99.9%): [5.693, 11.158] (assumes normal distribution)


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
# Warmup Iteration   1: 2.141 ops/ms
# Warmup Iteration   2: 6.380 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 7.825 ops/ms
Iteration   3: 8.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.999 ±(99.9%) 4.132 ops/ms [Average]
  (min, avg, max) = (7.825, 7.999, 8.256), stdev = 0.227
  CI (99.9%): [3.867, 12.132] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 4.734 ops/ms
# Warmup Iteration   3: 6.601 ops/ms
Iteration   1: 6.522 ops/ms
Iteration   2: 6.796 ops/ms
Iteration   3: 6.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.728 ±(99.9%) 3.327 ops/ms [Average]
  (min, avg, max) = (6.522, 6.728, 6.867), stdev = 0.182
  CI (99.9%): [3.401, 10.055] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.433 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.001 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.010 ms/op
Iteration   1: 4.264 ±(99.9%) 0.008 ms/op
Iteration   2: 4.221 ±(99.9%) 0.005 ms/op
Iteration   3: 4.064 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.183 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (4.064, 4.183, 4.264), stdev = 0.106
  CI (99.9%): [2.258, 6.108] (assumes normal distribution)


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
# Warmup Iteration   1: 12.900 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.006 ms/op
Iteration   1: 3.938 ±(99.9%) 0.006 ms/op
Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
Iteration   3: 3.807 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.874 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.807, 3.874, 3.938), stdev = 0.065
  CI (99.9%): [2.680, 5.068] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.321 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.007 ms/op
Iteration   1: 4.009 ±(99.9%) 0.008 ms/op
Iteration   2: 3.867 ±(99.9%) 0.009 ms/op
Iteration   3: 4.257 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.044 ±(99.9%) 3.601 ms/op [Average]
  (min, avg, max) = (3.867, 4.044, 4.257), stdev = 0.197
  CI (99.9%): [0.443, 7.645] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.585 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.704 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.936 ±(99.9%) 0.008 ms/op
Iteration   1: 4.823 ±(99.9%) 0.011 ms/op
Iteration   2: 4.772 ±(99.9%) 0.014 ms/op
Iteration   3: 4.824 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.806 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (4.772, 4.806, 4.824), stdev = 0.030
  CI (99.9%): [4.267, 5.346] (assumes normal distribution)


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
# Warmup Iteration   1: 14.023 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.676 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.912 ±(99.9%) 0.023 ms/op
Iteration   1: 4.232 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.025 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  10.704 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 4.229 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  26.554 ms/op
                 createUser·p0.9999: 33.260 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   3: 4.198 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.046 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 33.121 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 227484
  mean =      4.220 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 164 
    [ 2.500,  5.000) = 205662 
    [ 5.000,  7.500) = 17003 
    [ 7.500, 10.000) = 3316 
    [10.000, 12.500) = 786 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     19.566 ms/op
     p(99.9900) =     32.891 ms/op
     p(99.9990) =     33.781 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 12.399 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
Iteration   1: 4.056 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   7.938 ms/op
                 existUser·p0.999:  25.199 ms/op
                 existUser·p0.9999: 31.756 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   2: 3.997 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.796 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.511 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   7.922 ms/op
                 existUser·p0.999:  12.352 ms/op
                 existUser·p0.9999: 30.081 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  13.598 ms/op
                 existUser·p0.9999: 33.513 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240413
  mean =      3.993 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 241 
    [ 2.500,  5.000) = 225518 
    [ 5.000,  7.500) = 11147 
    [ 7.500, 10.000) = 2727 
    [10.000, 12.500) = 480 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     13.903 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     34.116 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 14.456 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.014 ms/op
Iteration   1: 4.126 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  22.804 ms/op
                 getUser·p0.9999: 32.086 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   2: 3.906 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  13.422 ms/op
                 getUser·p0.9999: 28.863 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 4.062 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.635 ms/op
                 getUser·p0.999:  25.657 ms/op
                 getUser·p0.9999: 30.286 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238089
  mean =      4.029 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 225248 
    [ 5.000,  7.500) = 9137 
    [ 7.500, 10.000) = 2691 
    [10.000, 12.500) = 535 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     22.214 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     33.439 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 15.170 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 6.419 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.051 ±(99.9%) 0.018 ms/op
Iteration   1: 4.763 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  23.130 ms/op
                 listUser·p0.9999: 33.059 ms/op
                 listUser·p1.00:   35.193 ms/op

Iteration   2: 4.711 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 24.943 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.833 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 20.626 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201146
  mean =      4.768 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 164711 
    [ 5.000,  7.500) = 31855 
    [ 7.500, 10.000) = 3388 
    [10.000, 12.500) = 623 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.028 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     19.618 ms/op
     p(99.9900) =     32.109 ms/op
     p(99.9990) =     34.661 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.208 ± 4.831  ops/ms
ClientPb.existUser                       thrpt       3   8.425 ± 2.732  ops/ms
ClientPb.getUser                         thrpt       3   7.999 ± 4.132  ops/ms
ClientPb.listUser                        thrpt       3   6.728 ± 3.327  ops/ms
ClientPb.createUser                       avgt       3   4.183 ± 1.925   ms/op
ClientPb.existUser                        avgt       3   3.874 ± 1.194   ms/op
ClientPb.getUser                          avgt       3   4.044 ± 3.601   ms/op
ClientPb.listUser                         avgt       3   4.806 ± 0.540   ms/op
ClientPb.createUser                     sample  227484   4.220 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.430           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.716           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.566           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.891           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  240413   3.993 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.561           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.448           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.053           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.903           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.440           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  238089   4.029 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.462           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.069           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.214           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.638           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  201146   4.768 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.028           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.618           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.109           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.193           ms/op
