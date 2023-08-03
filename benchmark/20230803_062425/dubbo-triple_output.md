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
# Warmup Iteration   1: 1.157 ops/ms
# Warmup Iteration   2: 2.617 ops/ms
# Warmup Iteration   3: 5.577 ops/ms
Iteration   1: 5.448 ops/ms
Iteration   2: 5.984 ops/ms
Iteration   3: 6.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.816 ±(99.9%) 5.821 ops/ms [Average]
  (min, avg, max) = (5.448, 5.816, 6.015), stdev = 0.319
  CI (99.9%): [≈ 0, 11.637] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.760 ops/ms
# Warmup Iteration   2: 5.142 ops/ms
# Warmup Iteration   3: 5.952 ops/ms
Iteration   1: 6.003 ops/ms
Iteration   2: 6.033 ops/ms
Iteration   3: 6.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.015 ±(99.9%) 0.287 ops/ms [Average]
  (min, avg, max) = (6.003, 6.015, 6.033), stdev = 0.016
  CI (99.9%): [5.728, 6.303] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.608 ops/ms
# Warmup Iteration   2: 4.931 ops/ms
# Warmup Iteration   3: 5.684 ops/ms
Iteration   1: 5.692 ops/ms
Iteration   2: 5.828 ops/ms
Iteration   3: 6.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.857 ±(99.9%) 3.304 ops/ms [Average]
  (min, avg, max) = (5.692, 5.857, 6.051), stdev = 0.181
  CI (99.9%): [2.553, 9.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.634 ops/ms
# Warmup Iteration   2: 3.875 ops/ms
# Warmup Iteration   3: 4.767 ops/ms
Iteration   1: 4.902 ops/ms
Iteration   2: 4.879 ops/ms
Iteration   3: 4.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.923 ±(99.9%) 1.036 ops/ms [Average]
  (min, avg, max) = (4.879, 4.923, 4.987), stdev = 0.057
  CI (99.9%): [3.887, 5.958] (assumes normal distribution)


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
# Warmup Iteration   1: 18.561 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 7.470 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.817 ±(99.9%) 0.011 ms/op
Iteration   1: 5.842 ±(99.9%) 0.011 ms/op
Iteration   2: 5.511 ±(99.9%) 0.015 ms/op
Iteration   3: 5.635 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.663 ±(99.9%) 3.050 ms/op [Average]
  (min, avg, max) = (5.511, 5.663, 5.842), stdev = 0.167
  CI (99.9%): [2.612, 8.713] (assumes normal distribution)


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
# Warmup Iteration   1: 16.568 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.936 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.116 ±(99.9%) 0.012 ms/op
Iteration   1: 5.364 ±(99.9%) 0.008 ms/op
Iteration   2: 5.227 ±(99.9%) 0.013 ms/op
Iteration   3: 5.187 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.259 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (5.187, 5.259, 5.364), stdev = 0.093
  CI (99.9%): [3.564, 6.955] (assumes normal distribution)


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
# Warmup Iteration   1: 17.201 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.422 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.554 ±(99.9%) 0.008 ms/op
Iteration   1: 5.449 ±(99.9%) 0.013 ms/op
Iteration   2: 5.431 ±(99.9%) 0.011 ms/op
Iteration   3: 5.393 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.424 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (5.393, 5.424, 5.449), stdev = 0.028
  CI (99.9%): [4.908, 5.941] (assumes normal distribution)


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
# Warmup Iteration   1: 19.928 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 7.976 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.566 ±(99.9%) 0.015 ms/op
Iteration   1: 6.469 ±(99.9%) 0.016 ms/op
Iteration   2: 6.548 ±(99.9%) 0.010 ms/op
Iteration   3: 6.411 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.476 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (6.411, 6.476, 6.548), stdev = 0.069
  CI (99.9%): [5.225, 7.727] (assumes normal distribution)


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
# Warmup Iteration   1: 16.899 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 6.904 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.047 ±(99.9%) 0.030 ms/op
Iteration   1: 5.501 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.963 ms/op
                 createUser·p0.99:   10.715 ms/op
                 createUser·p0.999:  24.838 ms/op
                 createUser·p0.9999: 28.410 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   2: 5.475 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.466 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   11.285 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 29.753 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   3: 5.501 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.709 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   10.764 ms/op
                 createUser·p0.999:  29.321 ms/op
                 createUser·p0.9999: 36.844 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174633
  mean =      5.492 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 71242 
    [ 5.000,  7.500) = 92761 
    [ 7.500, 10.000) = 7859 
    [10.000, 12.500) = 1876 
    [12.500, 15.000) = 401 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     24.993 ms/op
     p(99.9900) =     36.604 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 17.943 ±(99.9%) 0.331 ms/op
# Warmup Iteration   2: 6.547 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.378 ±(99.9%) 0.020 ms/op
Iteration   1: 5.498 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   7.176 ms/op
                 existUser·p0.95:   8.339 ms/op
                 existUser·p0.99:   11.272 ms/op
                 existUser·p0.999:  24.374 ms/op
                 existUser·p0.9999: 26.343 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 5.226 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.404 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.225 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  13.828 ms/op
                 existUser·p0.9999: 27.193 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   3: 5.281 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  28.836 ms/op
                 existUser·p0.9999: 35.389 ms/op
                 existUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179972
  mean =      5.333 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 90534 
    [ 5.000,  7.500) = 78991 
    [ 7.500, 10.000) = 8039 
    [10.000, 12.500) = 1792 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     17.335 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     35.940 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 16.064 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.813 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.465 ±(99.9%) 0.022 ms/op
Iteration   1: 5.505 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   7.183 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   13.189 ms/op
                 getUser·p0.999:  23.292 ms/op
                 getUser·p0.9999: 27.942 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 5.637 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.217 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   11.125 ms/op
                 getUser·p0.999:  14.944 ms/op
                 getUser·p0.9999: 31.981 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 5.621 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.601 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   8.438 ms/op
                 getUser·p0.99:   11.387 ms/op
                 getUser·p0.999:  28.126 ms/op
                 getUser·p0.9999: 31.752 ms/op
                 getUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171776
  mean =      5.587 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 69044 
    [ 5.000,  7.500) = 88090 
    [ 7.500, 10.000) = 10808 
    [10.000, 12.500) = 2435 
    [12.500, 15.000) = 944 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     12.095 ms/op
     p(99.9000) =     22.271 ms/op
     p(99.9900) =     31.544 ms/op
     p(99.9990) =     32.797 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 20.454 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 7.675 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.531 ±(99.9%) 0.027 ms/op
Iteration   1: 6.523 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   13.877 ms/op
                 listUser·p0.999:  27.029 ms/op
                 listUser·p0.9999: 31.097 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 6.621 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   14.434 ms/op
                 listUser·p0.999:  30.857 ms/op
                 listUser·p0.9999: 36.121 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   3: 6.049 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.191 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 28.392 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150228
  mean =      6.388 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 16057 
    [ 5.000,  7.500) = 114080 
    [ 7.500, 10.000) = 14203 
    [10.000, 12.500) = 3648 
    [12.500, 15.000) = 1287 
    [15.000, 17.500) = 478 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.630 ms/op
     p(50.0000) =      6.005 ms/op
     p(90.0000) =      7.979 ms/op
     p(95.0000) =      9.446 ms/op
     p(99.0000) =     13.550 ms/op
     p(99.9000) =     27.157 ms/op
     p(99.9900) =     35.257 ms/op
     p(99.9990) =     36.340 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.816 ± 5.821  ops/ms
ClientPb.existUser                       thrpt       3   6.015 ± 0.287  ops/ms
ClientPb.getUser                         thrpt       3   5.857 ± 3.304  ops/ms
ClientPb.listUser                        thrpt       3   4.923 ± 1.036  ops/ms
ClientPb.createUser                       avgt       3   5.663 ± 3.050   ms/op
ClientPb.existUser                        avgt       3   5.259 ± 1.696   ms/op
ClientPb.getUser                          avgt       3   5.424 ± 0.516   ms/op
ClientPb.listUser                         avgt       3   6.476 ± 1.251   ms/op
ClientPb.createUser                     sample  174633   5.492 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.812           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.889           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.961           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.993           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.604           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.224           ms/op
ClientPb.existUser                      sample  179972   5.333 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.437           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.472           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  171776   5.587 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.184           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.271           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  150228   6.388 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.005           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.446           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.550           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.157           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.257           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
