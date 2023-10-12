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
# Warmup Iteration   1: 1.059 ops/ms
# Warmup Iteration   2: 2.212 ops/ms
# Warmup Iteration   3: 4.772 ops/ms
Iteration   1: 5.165 ops/ms
Iteration   2: 5.475 ops/ms
Iteration   3: 5.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.351 ±(99.9%) 2.985 ops/ms [Average]
  (min, avg, max) = (5.165, 5.351, 5.475), stdev = 0.164
  CI (99.9%): [2.365, 8.336] (assumes normal distribution)


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
# Warmup Iteration   1: 1.494 ops/ms
# Warmup Iteration   2: 4.139 ops/ms
# Warmup Iteration   3: 5.609 ops/ms
Iteration   1: 5.939 ops/ms
Iteration   2: 5.739 ops/ms
Iteration   3: 5.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.826 ±(99.9%) 1.871 ops/ms [Average]
  (min, avg, max) = (5.739, 5.826, 5.939), stdev = 0.103
  CI (99.9%): [3.955, 7.697] (assumes normal distribution)


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
# Warmup Iteration   1: 1.626 ops/ms
# Warmup Iteration   2: 4.616 ops/ms
# Warmup Iteration   3: 5.430 ops/ms
Iteration   1: 5.287 ops/ms
Iteration   2: 5.379 ops/ms
Iteration   3: 5.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.502 ±(99.9%) 5.404 ops/ms [Average]
  (min, avg, max) = (5.287, 5.502, 5.840), stdev = 0.296
  CI (99.9%): [0.097, 10.906] (assumes normal distribution)


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
# Warmup Iteration   1: 1.398 ops/ms
# Warmup Iteration   2: 3.566 ops/ms
# Warmup Iteration   3: 4.545 ops/ms
Iteration   1: 4.635 ops/ms
Iteration   2: 4.929 ops/ms
Iteration   3: 4.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.783 ±(99.9%) 2.678 ops/ms [Average]
  (min, avg, max) = (4.635, 4.783, 4.929), stdev = 0.147
  CI (99.9%): [2.105, 7.460] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 21.160 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 7.474 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.007 ±(99.9%) 0.010 ms/op
Iteration   1: 6.035 ±(99.9%) 0.010 ms/op
Iteration   2: 5.496 ±(99.9%) 0.020 ms/op
Iteration   3: 5.687 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.739 ±(99.9%) 4.987 ms/op [Average]
  (min, avg, max) = (5.496, 5.739, 6.035), stdev = 0.273
  CI (99.9%): [0.753, 10.726] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.728 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.521 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.528 ±(99.9%) 0.007 ms/op
Iteration   1: 5.391 ±(99.9%) 0.011 ms/op
Iteration   2: 5.336 ±(99.9%) 0.010 ms/op
Iteration   3: 5.214 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.314 ±(99.9%) 1.648 ms/op [Average]
  (min, avg, max) = (5.214, 5.314, 5.391), stdev = 0.090
  CI (99.9%): [3.665, 6.962] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.414 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.705 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.880 ±(99.9%) 0.010 ms/op
Iteration   1: 5.847 ±(99.9%) 0.006 ms/op
Iteration   2: 5.790 ±(99.9%) 0.009 ms/op
Iteration   3: 5.892 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.843 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (5.790, 5.843, 5.892), stdev = 0.051
  CI (99.9%): [4.904, 6.782] (assumes normal distribution)


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
# Warmup Iteration   1: 19.067 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 8.767 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.892 ±(99.9%) 0.014 ms/op
Iteration   1: 6.835 ±(99.9%) 0.019 ms/op
Iteration   2: 6.738 ±(99.9%) 0.016 ms/op
Iteration   3: 6.493 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.689 ±(99.9%) 3.218 ms/op [Average]
  (min, avg, max) = (6.493, 6.689, 6.835), stdev = 0.176
  CI (99.9%): [3.471, 9.906] (assumes normal distribution)


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
# Warmup Iteration   1: 19.266 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 7.076 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.026 ms/op
Iteration   1: 5.677 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   7.856 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  25.974 ms/op
                 createUser·p0.9999: 27.754 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   2: 5.654 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   11.616 ms/op
                 createUser·p0.999:  28.518 ms/op
                 createUser·p0.9999: 32.441 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   3: 5.675 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.922 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   11.054 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 31.562 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169219
  mean =      5.669 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 50204 
    [ 5.000,  7.500) = 108669 
    [ 7.500, 10.000) = 7576 
    [10.000, 12.500) = 1698 
    [12.500, 15.000) = 546 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     26.345 ms/op
     p(99.9900) =     31.460 ms/op
     p(99.9990) =     32.657 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 16.089 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.237 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.590 ±(99.9%) 0.022 ms/op
Iteration   1: 5.513 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.767 ms/op
                 existUser·p0.95:   8.290 ms/op
                 existUser·p0.99:   11.600 ms/op
                 existUser·p0.999:  19.530 ms/op
                 existUser·p0.9999: 27.859 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   2: 5.499 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.466 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   6.701 ms/op
                 existUser·p0.95:   7.422 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  26.713 ms/op
                 existUser·p0.9999: 30.039 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   3: 5.572 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.602 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  29.393 ms/op
                 existUser·p0.9999: 39.322 ms/op
                 existUser·p1.00:   56.885 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173686
  mean =      5.528 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 62896 
    [ 5.000, 10.000) = 107956 
    [10.000, 15.000) = 2338 
    [15.000, 20.000) = 215 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 169 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     26.771 ms/op
     p(99.9900) =     38.601 ms/op
     p(99.9990) =     43.943 ms/op
     p(99.9999) =     56.885 ms/op
    p(100.0000) =     56.885 ms/op


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
# Warmup Iteration   1: 17.899 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.544 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.407 ±(99.9%) 0.018 ms/op
Iteration   1: 5.657 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   8.307 ms/op
                 getUser·p0.99:   11.534 ms/op
                 getUser·p0.999:  26.965 ms/op
                 getUser·p0.9999: 31.251 ms/op
                 getUser·p1.00:   35.258 ms/op

Iteration   2: 5.757 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.544 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.078 ms/op
                 getUser·p0.95:   8.503 ms/op
                 getUser·p0.99:   11.665 ms/op
                 getUser·p0.999:  26.404 ms/op
                 getUser·p0.9999: 29.965 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 5.617 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.744 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.636 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  16.171 ms/op
                 getUser·p0.9999: 32.352 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168998
  mean =      5.676 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 48402 
    [ 5.000,  7.500) = 109101 
    [ 7.500, 10.000) = 8514 
    [10.000, 12.500) = 1867 
    [12.500, 15.000) = 616 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     25.887 ms/op
     p(99.9900) =     31.565 ms/op
     p(99.9990) =     33.608 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.958 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 7.877 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 7.024 ±(99.9%) 0.029 ms/op
Iteration   1: 7.104 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   6.652 ms/op
                 listUser·p0.90:   8.815 ms/op
                 listUser·p0.95:   10.568 ms/op
                 listUser·p0.99:   14.598 ms/op
                 listUser·p0.999:  24.050 ms/op
                 listUser·p0.9999: 26.689 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 6.876 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.531 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  25.330 ms/op
                 listUser·p0.9999: 28.510 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   3: 6.573 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   13.206 ms/op
                 listUser·p0.999:  26.377 ms/op
                 listUser·p0.9999: 29.696 ms/op
                 listUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140219
  mean =      6.844 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 2171 
    [ 5.000,  7.500) = 113513 
    [ 7.500, 10.000) = 18569 
    [10.000, 12.500) = 3837 
    [12.500, 15.000) = 1244 
    [15.000, 17.500) = 455 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      6.463 ms/op
     p(90.0000) =      8.200 ms/op
     p(95.0000) =      9.601 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     25.322 ms/op
     p(99.9900) =     28.798 ms/op
     p(99.9990) =     30.224 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.351 ± 2.985  ops/ms
ClientPb.existUser                       thrpt       3   5.826 ± 1.871  ops/ms
ClientPb.getUser                         thrpt       3   5.502 ± 5.404  ops/ms
ClientPb.listUser                        thrpt       3   4.783 ± 2.678  ops/ms
ClientPb.createUser                       avgt       3   5.739 ± 4.987   ms/op
ClientPb.existUser                        avgt       3   5.314 ± 1.648   ms/op
ClientPb.getUser                          avgt       3   5.843 ± 0.939   ms/op
ClientPb.listUser                         avgt       3   6.689 ± 3.218   ms/op
ClientPb.createUser                     sample  169219   5.669 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.310           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.848           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.272           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.345           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.702           ms/op
ClientPb.existUser                      sample  173686   5.528 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.220           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.725           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.092           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.771           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.601           ms/op
ClientPb.existUser:existUser·p1.00      sample          56.885           ms/op
ClientPb.getUser                        sample  168998   5.676 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.579           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.159           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.256           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.887           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.565           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.258           ms/op
ClientPb.listUser                       sample  140219   6.844 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.280           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.463           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.200           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.664           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.409           ms/op
