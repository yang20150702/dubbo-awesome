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
# Warmup Iteration   1: 1.785 ops/ms
# Warmup Iteration   2: 3.930 ops/ms
# Warmup Iteration   3: 7.320 ops/ms
Iteration   1: 7.574 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.855 ±(99.9%) 4.438 ops/ms [Average]
  (min, avg, max) = (7.574, 7.855, 7.997), stdev = 0.243
  CI (99.9%): [3.417, 12.292] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.422 ops/ms
# Warmup Iteration   2: 7.711 ops/ms
# Warmup Iteration   3: 8.508 ops/ms
Iteration   1: 8.866 ops/ms
Iteration   2: 8.819 ops/ms
Iteration   3: 8.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.861 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (8.819, 8.861, 8.898), stdev = 0.040
  CI (99.9%): [8.129, 9.593] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.190 ops/ms
# Warmup Iteration   2: 7.015 ops/ms
# Warmup Iteration   3: 8.197 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 7.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.018 ±(99.9%) 3.041 ops/ms [Average]
  (min, avg, max) = (7.866, 8.018, 8.196), stdev = 0.167
  CI (99.9%): [4.977, 11.060] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.044 ops/ms
# Warmup Iteration   2: 5.487 ops/ms
# Warmup Iteration   3: 6.625 ops/ms
Iteration   1: 6.355 ops/ms
Iteration   2: 6.440 ops/ms
Iteration   3: 6.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.563 ±(99.9%) 5.267 ops/ms [Average]
  (min, avg, max) = (6.355, 6.563, 6.892), stdev = 0.289
  CI (99.9%): [1.296, 11.829] (assumes normal distribution)


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
# Warmup Iteration   1: 12.825 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.011 ms/op
Iteration   1: 3.889 ±(99.9%) 0.005 ms/op
Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
Iteration   3: 4.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.928 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.889, 3.928, 4.001), stdev = 0.063
  CI (99.9%): [2.780, 5.077] (assumes normal distribution)


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
# Warmup Iteration   1: 11.447 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.003 ms/op
Iteration   1: 3.694 ±(99.9%) 0.007 ms/op
Iteration   2: 3.746 ±(99.9%) 0.008 ms/op
Iteration   3: 3.798 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.746 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.694, 3.746, 3.798), stdev = 0.052
  CI (99.9%): [2.792, 4.701] (assumes normal distribution)


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
# Warmup Iteration   1: 12.685 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.004 ms/op
Iteration   1: 3.944 ±(99.9%) 0.003 ms/op
Iteration   2: 3.857 ±(99.9%) 0.004 ms/op
Iteration   3: 3.914 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.905 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.857, 3.905, 3.944), stdev = 0.044
  CI (99.9%): [3.098, 4.712] (assumes normal distribution)


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
# Warmup Iteration   1: 13.706 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.948 ±(99.9%) 0.007 ms/op
Iteration   1: 4.861 ±(99.9%) 0.007 ms/op
Iteration   2: 4.634 ±(99.9%) 0.012 ms/op
Iteration   3: 4.516 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.670 ±(99.9%) 3.200 ms/op [Average]
  (min, avg, max) = (4.516, 4.670, 4.861), stdev = 0.175
  CI (99.9%): [1.470, 7.870] (assumes normal distribution)


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
# Warmup Iteration   1: 12.641 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.830 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.019 ms/op
Iteration   1: 4.094 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.993 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 25.166 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  22.946 ms/op
                 createUser·p0.9999: 25.596 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.928 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  24.027 ms/op
                 createUser·p0.9999: 27.572 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237369
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 392 
    [ 2.500,  5.000) = 218417 
    [ 5.000,  7.500) = 15683 
    [ 7.500, 10.000) = 2091 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 87 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     28.004 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 11.748 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.012 ms/op
Iteration   1: 3.749 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  22.446 ms/op
                 existUser·p0.9999: 25.542 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 3.753 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  16.115 ms/op
                 existUser·p0.9999: 26.602 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.652 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  26.786 ms/op
                 existUser·p0.9999: 29.474 ms/op
                 existUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 258016
  mean =      3.718 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1248 
    [ 2.500,  5.000) = 245488 
    [ 5.000,  7.500) = 9154 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     17.234 ms/op
     p(99.9900) =     28.193 ms/op
     p(99.9990) =     29.702 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 11.858 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.014 ms/op
Iteration   1: 4.093 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   6.537 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  23.818 ms/op
                 getUser·p0.9999: 25.631 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 3.896 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  14.369 ms/op
                 getUser·p0.9999: 28.731 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 3.914 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.357 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  28.148 ms/op
                 getUser·p0.9999: 31.637 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241961
  mean =      3.966 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 500 
    [ 2.500,  5.000) = 225225 
    [ 5.000,  7.500) = 12193 
    [ 7.500, 10.000) = 3038 
    [10.000, 12.500) = 635 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     23.366 ms/op
     p(99.9900) =     31.156 ms/op
     p(99.9990) =     33.194 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 13.739 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.649 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.015 ms/op
Iteration   1: 4.571 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   9.462 ms/op
                 listUser·p0.999:  22.086 ms/op
                 listUser·p0.9999: 24.413 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 4.352 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  17.786 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 4.559 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   9.333 ms/op
                 listUser·p0.999:  16.646 ms/op
                 listUser·p0.9999: 22.639 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 213616
  mean =      4.492 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 186105 
    [ 5.000,  7.500) = 22355 
    [ 7.500, 10.000) = 3706 
    [10.000, 12.500) = 797 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     18.658 ms/op
     p(99.9900) =     23.319 ms/op
     p(99.9990) =     25.525 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.855 ± 4.438  ops/ms
ClientPb.existUser                       thrpt       3   8.861 ± 0.732  ops/ms
ClientPb.getUser                         thrpt       3   8.018 ± 3.041  ops/ms
ClientPb.listUser                        thrpt       3   6.563 ± 5.267  ops/ms
ClientPb.createUser                       avgt       3   3.928 ± 1.149   ms/op
ClientPb.existUser                        avgt       3   3.746 ± 0.955   ms/op
ClientPb.getUser                          avgt       3   3.905 ± 0.807   ms/op
ClientPb.listUser                         avgt       3   4.670 ± 3.200   ms/op
ClientPb.createUser                     sample  237369   4.043 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.036           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.315           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.411           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  258016   3.718 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.303           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.193           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.212           ms/op
ClientPb.getUser                        sample  241961   3.966 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.501           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.339           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  213616   4.492 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.409           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.658           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.319           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
