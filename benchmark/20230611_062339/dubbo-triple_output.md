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
# Warmup Iteration   1: 1.371 ops/ms
# Warmup Iteration   2: 3.035 ops/ms
# Warmup Iteration   3: 6.005 ops/ms
Iteration   1: 6.369 ops/ms
Iteration   2: 6.806 ops/ms
Iteration   3: 6.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.646 ±(99.9%) 4.404 ops/ms [Average]
  (min, avg, max) = (6.369, 6.646, 6.806), stdev = 0.241
  CI (99.9%): [2.242, 11.050] (assumes normal distribution)


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
# Warmup Iteration   1: 2.120 ops/ms
# Warmup Iteration   2: 6.115 ops/ms
# Warmup Iteration   3: 6.657 ops/ms
Iteration   1: 6.938 ops/ms
Iteration   2: 6.834 ops/ms
Iteration   3: 6.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.861 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (6.810, 6.861, 6.938), stdev = 0.068
  CI (99.9%): [5.620, 8.101] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.788 ops/ms
# Warmup Iteration   2: 5.321 ops/ms
# Warmup Iteration   3: 6.493 ops/ms
Iteration   1: 6.341 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.599 ±(99.9%) 4.166 ops/ms [Average]
  (min, avg, max) = (6.341, 6.599, 6.777), stdev = 0.228
  CI (99.9%): [2.433, 10.765] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.894 ops/ms
# Warmup Iteration   2: 4.766 ops/ms
# Warmup Iteration   3: 5.585 ops/ms
Iteration   1: 5.704 ops/ms
Iteration   2: 5.742 ops/ms
Iteration   3: 5.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.740 ±(99.9%) 0.619 ops/ms [Average]
  (min, avg, max) = (5.704, 5.740, 5.772), stdev = 0.034
  CI (99.9%): [5.121, 6.358] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.183 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 5.300 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.858 ±(99.9%) 0.013 ms/op
Iteration   1: 4.737 ±(99.9%) 0.007 ms/op
Iteration   2: 4.799 ±(99.9%) 0.012 ms/op
Iteration   3: 5.064 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.866 ±(99.9%) 3.165 ms/op [Average]
  (min, avg, max) = (4.737, 4.866, 5.064), stdev = 0.173
  CI (99.9%): [1.701, 8.032] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 13.882 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.010 ms/op
Iteration   1: 4.473 ±(99.9%) 0.013 ms/op
Iteration   2: 4.421 ±(99.9%) 0.015 ms/op
Iteration   3: 4.427 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.441 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (4.421, 4.441, 4.473), stdev = 0.028
  CI (99.9%): [3.923, 4.958] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.817 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.100 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.929 ±(99.9%) 0.010 ms/op
Iteration   1: 4.779 ±(99.9%) 0.009 ms/op
Iteration   2: 4.629 ±(99.9%) 0.013 ms/op
Iteration   3: 5.097 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.835 ±(99.9%) 4.360 ms/op [Average]
  (min, avg, max) = (4.629, 4.835, 5.097), stdev = 0.239
  CI (99.9%): [0.475, 9.195] (assumes normal distribution)


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
# Warmup Iteration   1: 14.457 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.609 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.923 ±(99.9%) 0.009 ms/op
Iteration   1: 5.392 ±(99.9%) 0.015 ms/op
Iteration   2: 5.503 ±(99.9%) 0.009 ms/op
Iteration   3: 5.556 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.484 ±(99.9%) 1.530 ms/op [Average]
  (min, avg, max) = (5.392, 5.484, 5.556), stdev = 0.084
  CI (99.9%): [3.954, 7.014] (assumes normal distribution)


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
# Warmup Iteration   1: 14.520 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.927 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.163 ±(99.9%) 0.024 ms/op
Iteration   1: 4.714 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.138 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.975 ms/op
                 createUser·p0.999:  16.502 ms/op
                 createUser·p0.9999: 25.344 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 5.033 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.283 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  22.030 ms/op
                 createUser·p0.9999: 27.577 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 4.797 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.414 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  20.781 ms/op
                 createUser·p0.9999: 27.219 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 198005
  mean =      4.844 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 138833 
    [ 5.000,  7.500) = 53001 
    [ 7.500, 10.000) = 4701 
    [10.000, 12.500) = 758 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     20.807 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     30.871 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 13.948 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.016 ms/op
Iteration   1: 4.812 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  21.961 ms/op
                 existUser·p0.9999: 30.748 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   2: 4.554 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   4.284 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  13.349 ms/op
                 existUser·p0.9999: 27.948 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   3: 4.570 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.001 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.546 ms/op
                 existUser·p0.95:   6.267 ms/op
                 existUser·p0.99:   8.282 ms/op
                 existUser·p0.999:  14.927 ms/op
                 existUser·p0.9999: 31.491 ms/op
                 existUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 206662
  mean =      4.643 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 119 
    [ 2.500,  5.000) = 159879 
    [ 5.000,  7.500) = 40848 
    [ 7.500, 10.000) = 4643 
    [10.000, 12.500) = 738 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     30.780 ms/op
     p(99.9990) =     31.881 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 13.468 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.197 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.101 ±(99.9%) 0.020 ms/op
Iteration   1: 4.903 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.442 ms/op
                 getUser·p0.50:   4.579 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   7.047 ms/op
                 getUser·p0.99:   10.093 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 26.442 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 4.826 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.987 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.603 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  14.243 ms/op
                 getUser·p0.9999: 27.030 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 4.826 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.646 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.906 ms/op
                 getUser·p0.95:   6.799 ms/op
                 getUser·p0.99:   9.601 ms/op
                 getUser·p0.999:  21.685 ms/op
                 getUser·p0.9999: 25.515 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 197633
  mean =      4.851 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 137309 
    [ 5.000,  7.500) = 53447 
    [ 7.500, 10.000) = 5202 
    [10.000, 12.500) = 1194 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     26.484 ms/op
     p(99.9990) =     27.729 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 16.045 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.375 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.833 ±(99.9%) 0.025 ms/op
Iteration   1: 5.553 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  22.704 ms/op
                 listUser·p0.9999: 33.358 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   2: 5.421 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   6.521 ms/op
                 listUser·p0.95:   7.397 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  24.475 ms/op
                 listUser·p0.9999: 28.092 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   3: 5.548 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   9.948 ms/op
                 listUser·p0.999:  19.868 ms/op
                 listUser·p0.9999: 21.897 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 174296
  mean =      5.507 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 64714 
    [ 5.000,  7.500) = 99750 
    [ 7.500, 10.000) = 7631 
    [10.000, 12.500) = 1434 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.005 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     21.565 ms/op
     p(99.9900) =     32.369 ms/op
     p(99.9990) =     33.738 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.646 ± 4.404  ops/ms
ClientPb.existUser                       thrpt       3   6.861 ± 1.240  ops/ms
ClientPb.getUser                         thrpt       3   6.599 ± 4.166  ops/ms
ClientPb.listUser                        thrpt       3   5.740 ± 0.619  ops/ms
ClientPb.createUser                       avgt       3   4.866 ± 3.165   ms/op
ClientPb.existUser                        avgt       3   4.441 ± 0.518   ms/op
ClientPb.getUser                          avgt       3   4.835 ± 4.360   ms/op
ClientPb.listUser                         avgt       3   5.484 ± 1.530   ms/op
ClientPb.createUser                     sample  198005   4.844 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.257           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.807           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.197           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  206662   4.643 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.565           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.652           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.946           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.056           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.780           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.047           ms/op
ClientPb.getUser                        sample  197633   4.851 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.442           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.683           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.939           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.484           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.017           ms/op
ClientPb.listUser                       sample  174296   5.507 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.005           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.404           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.565           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.369           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
