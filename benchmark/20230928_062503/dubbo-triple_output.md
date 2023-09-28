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
# Warmup Iteration   1: 1.326 ops/ms
# Warmup Iteration   2: 3.364 ops/ms
# Warmup Iteration   3: 5.885 ops/ms
Iteration   1: 5.988 ops/ms
Iteration   2: 5.942 ops/ms
Iteration   3: 6.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.996 ±(99.9%) 1.053 ops/ms [Average]
  (min, avg, max) = (5.942, 5.996, 6.057), stdev = 0.058
  CI (99.9%): [4.942, 7.049] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.825 ops/ms
# Warmup Iteration   2: 5.832 ops/ms
# Warmup Iteration   3: 6.288 ops/ms
Iteration   1: 6.646 ops/ms
Iteration   2: 6.687 ops/ms
Iteration   3: 6.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.695 ±(99.9%) 0.994 ops/ms [Average]
  (min, avg, max) = (6.646, 6.695, 6.754), stdev = 0.055
  CI (99.9%): [5.701, 7.690] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.892 ops/ms
# Warmup Iteration   2: 5.068 ops/ms
# Warmup Iteration   3: 5.885 ops/ms
Iteration   1: 5.958 ops/ms
Iteration   2: 6.365 ops/ms
Iteration   3: 6.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.256 ±(99.9%) 4.747 ops/ms [Average]
  (min, avg, max) = (5.958, 6.256, 6.443), stdev = 0.260
  CI (99.9%): [1.508, 11.003] (assumes normal distribution)


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
# Warmup Iteration   1: 1.664 ops/ms
# Warmup Iteration   2: 4.441 ops/ms
# Warmup Iteration   3: 4.993 ops/ms
Iteration   1: 5.288 ops/ms
Iteration   2: 5.237 ops/ms
Iteration   3: 5.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.285 ±(99.9%) 0.836 ops/ms [Average]
  (min, avg, max) = (5.237, 5.285, 5.329), stdev = 0.046
  CI (99.9%): [4.449, 6.121] (assumes normal distribution)


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
# Warmup Iteration   1: 17.064 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.030 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.444 ±(99.9%) 0.009 ms/op
Iteration   1: 5.358 ±(99.9%) 0.012 ms/op
Iteration   2: 5.147 ±(99.9%) 0.007 ms/op
Iteration   3: 5.130 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.212 ±(99.9%) 2.321 ms/op [Average]
  (min, avg, max) = (5.130, 5.212, 5.358), stdev = 0.127
  CI (99.9%): [2.891, 7.532] (assumes normal distribution)


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
# Warmup Iteration   1: 14.667 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.748 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.869 ±(99.9%) 0.005 ms/op
Iteration   1: 4.796 ±(99.9%) 0.011 ms/op
Iteration   2: 4.641 ±(99.9%) 0.010 ms/op
Iteration   3: 4.693 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.710 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (4.641, 4.710, 4.796), stdev = 0.079
  CI (99.9%): [3.274, 6.146] (assumes normal distribution)


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
# Warmup Iteration   1: 15.025 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.791 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.335 ±(99.9%) 0.006 ms/op
Iteration   1: 5.211 ±(99.9%) 0.011 ms/op
Iteration   2: 5.140 ±(99.9%) 0.007 ms/op
Iteration   3: 5.229 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.194 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (5.140, 5.194, 5.229), stdev = 0.047
  CI (99.9%): [4.335, 6.053] (assumes normal distribution)


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
# Warmup Iteration   1: 19.794 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.832 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.224 ±(99.9%) 0.012 ms/op
Iteration   1: 5.946 ±(99.9%) 0.012 ms/op
Iteration   2: 6.140 ±(99.9%) 0.011 ms/op
Iteration   3: 5.968 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.018 ±(99.9%) 1.939 ms/op [Average]
  (min, avg, max) = (5.946, 6.018, 6.140), stdev = 0.106
  CI (99.9%): [4.079, 7.957] (assumes normal distribution)


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
# Warmup Iteration   1: 15.209 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 6.266 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.579 ±(99.9%) 0.026 ms/op
Iteration   1: 4.946 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   4.661 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   9.945 ms/op
                 createUser·p0.999:  20.902 ms/op
                 createUser·p0.9999: 23.628 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 5.282 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   11.387 ms/op
                 createUser·p0.999:  22.035 ms/op
                 createUser·p0.9999: 25.002 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   3: 5.276 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.071 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   11.196 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 31.034 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185701
  mean =      5.163 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 107029 
    [ 5.000,  7.500) = 69292 
    [ 7.500, 10.000) = 6555 
    [10.000, 12.500) = 1764 
    [12.500, 15.000) = 503 
    [15.000, 17.500) = 267 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.071 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     28.157 ms/op
     p(99.9990) =     32.160 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 14.065 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.354 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.020 ±(99.9%) 0.017 ms/op
Iteration   1: 4.954 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   10.797 ms/op
                 existUser·p0.999:  21.085 ms/op
                 existUser·p0.9999: 23.417 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 5.063 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.347 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   10.551 ms/op
                 existUser·p0.999:  23.478 ms/op
                 existUser·p0.9999: 26.161 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 5.115 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.302 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.422 ms/op
                 existUser·p0.99:   11.370 ms/op
                 existUser·p0.999:  27.143 ms/op
                 existUser·p0.9999: 32.520 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190226
  mean =      5.043 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 123796 
    [ 5.000,  7.500) = 56675 
    [ 7.500, 10.000) = 7007 
    [10.000, 12.500) = 1701 
    [12.500, 15.000) = 569 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     30.080 ms/op
     p(99.9990) =     33.076 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 16.328 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.008 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.363 ±(99.9%) 0.022 ms/op
Iteration   1: 5.304 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.954 ms/op
                 getUser·p0.99:   12.086 ms/op
                 getUser·p0.999:  24.631 ms/op
                 getUser·p0.9999: 27.917 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   2: 5.289 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.617 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  25.792 ms/op
                 getUser·p0.9999: 30.340 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   3: 5.080 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   10.650 ms/op
                 getUser·p0.999:  24.411 ms/op
                 getUser·p0.9999: 33.862 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183774
  mean =      5.222 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 104565 
    [ 5.000,  7.500) = 67958 
    [ 7.500, 10.000) = 7790 
    [10.000, 12.500) = 2219 
    [12.500, 15.000) = 772 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     32.068 ms/op
     p(99.9990) =     34.024 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 16.560 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.551 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.248 ±(99.9%) 0.025 ms/op
Iteration   1: 6.032 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.076 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   12.960 ms/op
                 listUser·p0.999:  25.820 ms/op
                 listUser·p0.9999: 30.749 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   2: 6.079 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  28.029 ms/op
                 listUser·p0.9999: 34.241 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   3: 5.893 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   11.768 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.467 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159902
  mean =      6.000 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 26821 
    [ 5.000,  7.500) = 119172 
    [ 7.500, 10.000) = 10712 
    [10.000, 12.500) = 1940 
    [12.500, 15.000) = 654 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     24.153 ms/op
     p(99.9900) =     31.829 ms/op
     p(99.9990) =     34.891 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.996 ± 1.053  ops/ms
ClientPb.existUser                       thrpt       3   6.695 ± 0.994  ops/ms
ClientPb.getUser                         thrpt       3   6.256 ± 4.747  ops/ms
ClientPb.listUser                        thrpt       3   5.285 ± 0.836  ops/ms
ClientPb.createUser                       avgt       3   5.212 ± 2.321   ms/op
ClientPb.existUser                        avgt       3   4.710 ± 1.436   ms/op
ClientPb.getUser                          avgt       3   5.194 ± 0.859   ms/op
ClientPb.listUser                         avgt       3   6.018 ± 1.939   ms/op
ClientPb.createUser                     sample  185701   5.163 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.841           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.504           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.504           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.879           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.157           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  190226   5.043 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.472           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.080           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.194           ms/op
ClientPb.getUser                        sample  183774   5.222 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.049           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.864           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.370           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.674           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.068           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  159902   6.000 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.290           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.829           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.153           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.931           ms/op
