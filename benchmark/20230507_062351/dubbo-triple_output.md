# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.151 ops/ms
# Warmup Iteration   2: 2.840 ops/ms
# Warmup Iteration   3: 4.368 ops/ms
Iteration   1: 5.491 ops/ms
Iteration   2: 7.588 ops/ms
Iteration   3: 7.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.823 ±(99.9%) 21.122 ops/ms [Average]
  (min, avg, max) = (5.491, 6.823, 7.588), stdev = 1.158
  CI (99.9%): [≈ 0, 27.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.551 ops/ms
# Warmup Iteration   2: 3.111 ops/ms
# Warmup Iteration   3: 4.980 ops/ms
Iteration   1: 4.203 ops/ms
Iteration   2: 6.341 ops/ms
Iteration   3: 5.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.405 ±(99.9%) 19.957 ops/ms [Average]
  (min, avg, max) = (4.203, 5.405, 6.341), stdev = 1.094
  CI (99.9%): [≈ 0, 25.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.200 ops/ms
# Warmup Iteration   2: 3.540 ops/ms
# Warmup Iteration   3: 4.879 ops/ms
Iteration   1: 5.062 ops/ms
Iteration   2: 7.058 ops/ms
Iteration   3: 4.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.427 ±(99.9%) 27.049 ops/ms [Average]
  (min, avg, max) = (4.161, 5.427, 7.058), stdev = 1.483
  CI (99.9%): [≈ 0, 32.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 4.486 ops/ms
# Warmup Iteration   3: 3.434 ops/ms
Iteration   1: 4.646 ops/ms
Iteration   2: 3.682 ops/ms
Iteration   3: 3.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.019 ±(99.9%) 9.926 ops/ms [Average]
  (min, avg, max) = (3.682, 4.019, 4.646), stdev = 0.544
  CI (99.9%): [≈ 0, 13.945] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.345 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.950 ±(99.9%) 0.015 ms/op
Iteration   1: 7.124 ±(99.9%) 0.019 ms/op
Iteration   2: 10.561 ±(99.9%) 0.030 ms/op
Iteration   3: 5.955 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.880 ±(99.9%) 43.676 ms/op [Average]
  (min, avg, max) = (5.955, 7.880, 10.561), stdev = 2.394
  CI (99.9%): [≈ 0, 51.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.454 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.216 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.005 ms/op
Iteration   1: 5.230 ±(99.9%) 0.009 ms/op
Iteration   2: 6.998 ±(99.9%) 0.015 ms/op
Iteration   3: 6.654 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.294 ±(99.9%) 17.102 ms/op [Average]
  (min, avg, max) = (5.230, 6.294, 6.998), stdev = 0.937
  CI (99.9%): [≈ 0, 23.396] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.842 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 12.281 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 6.770 ±(99.9%) 0.014 ms/op
Iteration   1: 4.327 ±(99.9%) 0.007 ms/op
Iteration   2: 4.212 ±(99.9%) 0.006 ms/op
Iteration   3: 4.299 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.280 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (4.212, 4.280, 4.327), stdev = 0.060
  CI (99.9%): [3.183, 5.376] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.823 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.066 ±(99.9%) 0.006 ms/op
Iteration   1: 4.697 ±(99.9%) 0.013 ms/op
Iteration   2: 4.718 ±(99.9%) 0.019 ms/op
Iteration   3: 4.939 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.784 ±(99.9%) 2.449 ms/op [Average]
  (min, avg, max) = (4.697, 4.784, 4.939), stdev = 0.134
  CI (99.9%): [2.336, 7.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.038 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.017 ms/op
Iteration   1: 3.828 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   2.142 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  10.723 ms/op
                 createUser·p0.9999: 22.697 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 4.212 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.071 ms/op
                 createUser·p0.95:   6.242 ms/op
                 createUser·p0.99:   8.488 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 29.432 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   3: 3.812 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  13.898 ms/op
                 createUser·p0.9999: 30.114 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243492
  mean =      3.942 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 344 
    [ 2.500,  5.000) = 231102 
    [ 5.000,  7.500) = 10144 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.869 ms/op
     p(99.9900) =     29.087 ms/op
     p(99.9990) =     30.379 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.110 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.011 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.790 ms/op
                 existUser·p0.999:  14.647 ms/op
                 existUser·p0.9999: 24.705 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.787 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.786 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  22.628 ms/op
                 existUser·p0.9999: 26.629 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   3: 3.863 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  13.127 ms/op
                 existUser·p0.9999: 27.432 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247769
  mean =      3.875 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 365 
    [ 2.500,  5.000) = 232927 
    [ 5.000,  7.500) = 11621 
    [ 7.500, 10.000) = 2069 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     13.863 ms/op
     p(99.9900) =     26.892 ms/op
     p(99.9990) =     28.317 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.570 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.885 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.018 ms/op
Iteration   1: 4.113 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   8.342 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 26.779 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 4.027 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.522 ms/op
                 getUser·p0.999:  24.269 ms/op
                 getUser·p0.9999: 32.213 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  14.245 ms/op
                 getUser·p0.9999: 31.658 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235782
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 222950 
    [ 5.000,  7.500) = 10010 
    [ 7.500, 10.000) = 1971 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.453 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.193 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.295 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.087 ±(99.9%) 0.019 ms/op
Iteration   1: 4.664 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  25.180 ms/op
                 listUser·p0.9999: 27.759 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   2: 4.749 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.777 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.572 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  16.576 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205889
  mean =      4.661 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 178869 
    [ 5.000,  7.500) = 21791 
    [ 7.500, 10.000) = 4090 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     28.231 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   6.823 ± 21.122  ops/ms
ClientPb.existUser                       thrpt       3   5.405 ± 19.957  ops/ms
ClientPb.getUser                         thrpt       3   5.427 ± 27.049  ops/ms
ClientPb.listUser                        thrpt       3   4.019 ±  9.926  ops/ms
ClientPb.createUser                       avgt       3   7.880 ± 43.676   ms/op
ClientPb.existUser                        avgt       3   6.294 ± 17.102   ms/op
ClientPb.getUser                          avgt       3   4.280 ±  1.096   ms/op
ClientPb.listUser                         avgt       3   4.784 ±  2.449   ms/op
ClientPb.createUser                     sample  243492   3.942 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.323            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.473            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119            ms/op
ClientPb.createUser:createUser·p0.999   sample          14.869            ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.087            ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573            ms/op
ClientPb.existUser                      sample  247769   3.875 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.818            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.186            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.643            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.863            ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.892            ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606            ms/op
ClientPb.getUser                        sample  235782   4.068 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.661            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.684            ms/op
ClientPb.getUser:getUser·p0.999         sample          16.908            ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.621            ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882            ms/op
ClientPb.listUser                       sample  205889   4.661 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.272            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.153            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.808            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880            ms/op
ClientPb.listUser:listUser·p0.999       sample          20.644            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.394            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.672            ms/op
