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
# Warmup Iteration   1: 1.630 ops/ms
# Warmup Iteration   2: 3.793 ops/ms
# Warmup Iteration   3: 6.748 ops/ms
Iteration   1: 7.043 ops/ms
Iteration   2: 7.656 ops/ms
Iteration   3: 7.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.281 ±(99.9%) 5.998 ops/ms [Average]
  (min, avg, max) = (7.043, 7.281, 7.656), stdev = 0.329
  CI (99.9%): [1.283, 13.280] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 7.376 ops/ms
Iteration   1: 8.128 ops/ms
Iteration   2: 7.951 ops/ms
Iteration   3: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.997 ±(99.9%) 2.104 ops/ms [Average]
  (min, avg, max) = (7.911, 7.997, 8.128), stdev = 0.115
  CI (99.9%): [5.893, 10.101] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.961 ops/ms
# Warmup Iteration   2: 5.763 ops/ms
# Warmup Iteration   3: 7.873 ops/ms
Iteration   1: 7.670 ops/ms
Iteration   2: 7.835 ops/ms
Iteration   3: 8.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.928 ±(99.9%) 5.749 ops/ms [Average]
  (min, avg, max) = (7.670, 7.928, 8.280), stdev = 0.315
  CI (99.9%): [2.179, 13.677] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.287 ops/ms
# Warmup Iteration   2: 5.446 ops/ms
# Warmup Iteration   3: 6.684 ops/ms
Iteration   1: 6.721 ops/ms
Iteration   2: 7.025 ops/ms
Iteration   3: 6.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.869 ±(99.9%) 2.779 ops/ms [Average]
  (min, avg, max) = (6.721, 6.869, 7.025), stdev = 0.152
  CI (99.9%): [4.090, 9.648] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.896 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.405 ±(99.9%) 0.010 ms/op
Iteration   1: 4.094 ±(99.9%) 0.004 ms/op
Iteration   2: 3.977 ±(99.9%) 0.007 ms/op
Iteration   3: 3.942 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.004 ±(99.9%) 1.453 ms/op [Average]
  (min, avg, max) = (3.942, 4.004, 4.094), stdev = 0.080
  CI (99.9%): [2.551, 5.457] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.022 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.859 ±(99.9%) 0.003 ms/op
Iteration   2: 3.863 ±(99.9%) 0.012 ms/op
Iteration   3: 3.987 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.903 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.859, 3.903, 3.987), stdev = 0.073
  CI (99.9%): [2.580, 5.226] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.947 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.789 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.006 ms/op
Iteration   1: 4.146 ±(99.9%) 0.005 ms/op
Iteration   2: 4.027 ±(99.9%) 0.004 ms/op
Iteration   3: 4.159 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.111 ±(99.9%) 1.325 ms/op [Average]
  (min, avg, max) = (4.027, 4.111, 4.159), stdev = 0.073
  CI (99.9%): [2.786, 5.436] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.455 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.407 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.011 ms/op
Iteration   1: 4.850 ±(99.9%) 0.008 ms/op
Iteration   2: 4.866 ±(99.9%) 0.015 ms/op
Iteration   3: 4.577 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.764 ±(99.9%) 2.963 ms/op [Average]
  (min, avg, max) = (4.577, 4.764, 4.866), stdev = 0.162
  CI (99.9%): [1.801, 7.727] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.860 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.570 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.018 ms/op
Iteration   1: 4.015 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.163 ms/op
                 createUser·p0.99:   7.294 ms/op
                 createUser·p0.999:  24.773 ms/op
                 createUser·p0.9999: 29.525 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   2: 4.125 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.972 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  17.580 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   33.456 ms/op

Iteration   3: 4.052 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.887 ms/op
                 createUser·p0.999:  27.962 ms/op
                 createUser·p0.9999: 31.097 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236097
  mean =      4.063 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177 
    [ 2.500,  5.000) = 221529 
    [ 5.000,  7.500) = 12618 
    [ 7.500, 10.000) = 1099 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 83 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     33.290 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.925 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.623 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.014 ms/op
Iteration   1: 3.941 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.122 ms/op
                 existUser·p0.999:  12.516 ms/op
                 existUser·p0.9999: 32.571 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   2: 3.838 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.991 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   7.766 ms/op
                 existUser·p0.999:  25.035 ms/op
                 existUser·p0.9999: 32.233 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   3: 3.927 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  13.238 ms/op
                 existUser·p0.9999: 39.256 ms/op
                 existUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245961
  mean =      3.902 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 232799 
    [ 5.000, 10.000) = 12706 
    [10.000, 15.000) = 232 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 43 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.792 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     40.280 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 15.163 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.012 ms/op
Iteration   1: 4.266 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  25.099 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   2: 4.217 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  19.425 ms/op
                 getUser·p0.9999: 28.948 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   3: 4.162 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  13.346 ms/op
                 getUser·p0.9999: 34.296 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227723
  mean =      4.215 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 210311 
    [ 5.000,  7.500) = 12611 
    [ 7.500, 10.000) = 3415 
    [10.000, 12.500) = 949 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     33.127 ms/op
     p(99.9990) =     34.585 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 14.120 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.768 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.806 ±(99.9%) 0.017 ms/op
Iteration   1: 4.811 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 30.923 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 4.904 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  21.181 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 4.551 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 18.381 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201958
  mean =      4.751 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 170582 
    [ 5.000,  7.500) = 25825 
    [ 7.500, 10.000) = 4340 
    [10.000, 12.500) = 626 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.034 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     20.416 ms/op
     p(99.9900) =     30.861 ms/op
     p(99.9990) =     31.554 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.281 ± 5.998  ops/ms
ClientPb.existUser                       thrpt       3   7.997 ± 2.104  ops/ms
ClientPb.getUser                         thrpt       3   7.928 ± 5.749  ops/ms
ClientPb.listUser                        thrpt       3   6.869 ± 2.779  ops/ms
ClientPb.createUser                       avgt       3   4.004 ± 1.453   ms/op
ClientPb.existUser                        avgt       3   3.903 ± 1.323   ms/op
ClientPb.getUser                          avgt       3   4.111 ± 1.325   ms/op
ClientPb.listUser                         avgt       3   4.764 ± 2.963   ms/op
ClientPb.createUser                     sample  236097   4.063 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.127           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.805           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  245961   3.902 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.792           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.339           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.436           ms/op
ClientPb.getUser                        sample  227723   4.215 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.603           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.569           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.127           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.734           ms/op
ClientPb.listUser                       sample  201958   4.751 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.034           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.416           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.861           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.539           ms/op
